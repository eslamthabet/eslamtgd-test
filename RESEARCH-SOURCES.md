# اختيار إدارة المحتوى، 23 نوفمبر 2026

الاختيار: Pages CMS المستضاف + Jekyll الأصلي على GitHub Pages. محرر من المتصفح، صور، ملفات نصية في GitHub، من غير تشغيل برامج على كمبيوتر المستخدم.

| الطريق | مناسب؟ | القيد |
|---|---|---|
| Pages CMS | الأفضل هنا | يحتاج GitHub App، خدمة خارجية، تفعيل ومراجعة صلاحيات، واجهته مش مضمونة بالعربي بالكامل |
| Decap CMS | بديل أقوى في التخصيص | GitHub يحتاج خدمة مصادقة/Proxy أو مزود مستضاف؛ إعداد أكثر من اللازم للتجربة دي |
| تحرير Markdown داخل GitHub | بديل احتياطي مجاني | تفاصيل الملفات والتنسيق أقل راحة لغير التقني |

Pages CMS يعلن أن النسخة المستضافة مجانية 100% ومفتوحة المصدر MIT. لم أجد في صفحات التسعير/التعريف المفتوحة حصة استخدام رقمية أو SLA، لذلك لا أدّعي أنه بلا حدود أو أن الخدمة مضمونة. المحتوى والميديا في GitHub خاضعان لحدوده.

GitHub Free يحتاج مستودعًا علنيًا لهذا الاستخدام. حدود Pages: حجم منشور 1GB، نقل بيانات مرن 100GB شهريًا، وحد مرن 10 عمليات بناء في الساعة عند النشر من فرع، ومهلة بناء 10 دقائق. النشر قد يستغرق حتى 10 دقائق. تجنب رفع فيديوهات كبيرة، وكثرة الحفظ السريع ممكن تعمل بناء كتير. Pages لا يشغل PHP أو سيرفر WordPress. GitHub يقيد مواقع التجارة والمعاملات وSaaS؛ لم أجد في هذه الصفحة حظرًا عامًا على إعلانات مدونة محتوى، وده مش موافقة خاصة من GitHub أو Google.

المسودات خارج الموقع فقط وليست سرية في المستودع العلني. ما فيش مجتمع حقيقي أو تحليلات أو عدادات مشاهدة أو جدولة تلقائية مفعّلة.

## المصادر المقروءة
- Pages CMS، مجاني ومزايا المتصفح والموبايل: https://pagescms.org/
- التفعيل الرسمي: https://pagescms.org/docs/quick-start/
- مخطط المقالات: https://pagescms.org/docs/configuration/content/
- الملفات والتسمية: https://pagescms.org/docs/configuration/content/filename/
- الصور: https://pagescms.org/docs/configuration/media/
- اختيار التصنيف: https://pagescms.org/docs/configuration/fields/select/
- محرر النص: https://pagescms.org/docs/configuration/fields/rich-text/
- التاريخ: https://pagescms.org/docs/configuration/fields/date/
- مفاتيح النشر والأهمية: https://pagescms.org/docs/configuration/fields/boolean/
- Decap ومصادقة GitHub: https://decapcms.org/docs/github-backend/
- GitHub Pages والبناء والعلنية: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- الحدود: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
- تجربة مستخدم مستقلة مع Pages CMS وJekyll، 13 أبريل 2026، استُخدمت لفهم مخاطر التهيئة فقط والأولوية للتوثيق الرسمي الحالي: https://quintussential.com/archive/2026/04/13/Setting-Up-Pages-CMS-for-Jekyll/
- مراجع Google في ADSENSE-SETUP-NOTES.txt.

التحقق: بناء فعلي باستخدام Jekyll 3.10، فحص أحجام 320 و390 و1280، وتجربة مؤقتة لمقال منشور ومسودة وعلم featured وتصنيف وصورة. الملفات المؤقتة اتشالت من الحزمة. تسجيل دخول Pages CMS وحفظه في مستودع المستخدم لسه محتاجين تفويضه وتركيبه.
