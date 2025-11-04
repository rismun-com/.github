<p align="center">
  <img src="assets/rismun-logo-en.svg" alt="Rismun" width="220" />
</p>

# ريسمان

ريسمان شركة برمجيات إيرانية (تأسست 2009/1388) تبني منصات رقمية بالغة الأهمية للمؤسسات والقطاع العام. نتميز بمعماريات الخدمات المصغّرة والواجهات المصغّرة، وأنظمة API‑First، وتدفّقات بيانات آمنة تعمل داخل المقر أو في السُحب الخاصة/الهجينة. نمزج تفكير المنتج مع هندسة منضبطة لتقديم برمجيات موثوقة، قابلة للملاحظة، وتركّز على الخصوصية على نطاق واسع.

## لمحة عن الشركة
- الاسم بالفارسية: پردازش اطلاعات ریسمان
- المجالات: منصات الحكومة الإلكترونية، أتمتة المؤسسات، الأنظمة المالية/الإدارية
- نقاط التميّز: عمارة مبنية على المعايير، انضباط في التسليم، دعم ثنائي/ثلاثي اللغة (FA/EN/AR) مع RTL كامل

## ماذا نفعل
- هندسة المنصات
  - مسرّعات «منصة ريسمان الرقمية»: الهوية والوصول، سير العمل/BPMS، النماذج، المستندات، الإشعارات، مركز التكامل.
- تطوير المنتجات
  - من الاستكشاف إلى UX/UI ثم البناء والنشر والتشغيل؛ نتائج قابلة للقياس (SLI/SLO) وجداول إصدار واضحة.
- الخدمات المصغّرة والواجهات المصغّرة
  - تصميم قائم على المجال (DDD)، أنظمة مدفوعة بالأحداث، بوابة API وشبكة خدمات (Service Mesh)، قابلية التوسّع والنشر المستقل.
- التكامل وقابلية التشغيل البيني
  - REST/GraphQL/gRPC، الرسائل، Webhooks، وCDC؛ موصلات لأنظمة ERP/CRM/Tax والأنظمة الحكومية.
- سير العمل والأتمتة
  - نمذجة BPMN، اتفاقيات مستوى الخدمة، التوقيع الإلكتروني، مسارات التدقيق؛ امتثال للبيئات المنظمة.
- تمكين البيانات والذكاء الاصطناعي
  - خطوط بث البيانات، بحث/تحليلات، مخارج BI؛ إدخال ذكي وبحث معزّز بالاسترجاع (RAG) حيثما كان مناسبًا.
- السحابة وDevOps
  - حاويات، CI/CD، IaC، تشغيل Kubernetes؛ تسليم تدريجي وتماثل البيئات.
- الأمن والحَوْكمة
  - OIDC، RBAC/ABAC، تشفير أثناء النقل وفي السكون، التدقيق؛ خصوصية حسب التصميم وأقل امتياز.
- التدريب والدعم
  - تمكين، توثيق، ودعم طويل الأمد لضمان نجاح الاعتماد.

## المنتجات والحلول الرئيسية
- منصة ريسمان الرقمية (RDP)
  - أساس موحّد من خدمات مصغّرة وواجهات مصغّرة يوفّر الهوية، سير العمل، النماذج، المستندات، الإشعارات، التدقيق، ومركز التكامل.
  - التقنية: واجهات مصغّرة (Next.js، Module Federation)، خدمات مصغّرة (.NET، Node.js/NestJS)، gRPC داخلي، REST/GraphQL على الحافة، Kafka/RabbitMQ، PostgreSQL/MongoDB/Redis، OpenSearch، تخزين كائني متوافق مع S3، بوابة API، شبكة خدمات، OIDC، OpenTelemetry.

- RISAPP منخفضة الكود للنماذج والعمليات
  - محرر WYSIWYG، نماذج قائمة على المخططات، محرّك قواعد، تدفقات متعددة الخطوات، إدارة الإصدارات، الأعلام الوظيفية، PWA، وجاهزية للجوال.
  - التقنية: واجهات مصغّرة بـ Next.js، خدمات خلفية Node.js/NestJS أو .NET، بوابة GraphQL، gRPC بين الخدمات، JSON Schema، PostgreSQL + MongoDB، Redis.

- الأتمتة المكتبية وسير العمل (BPMS)
  - نمذجة BPMN، المراسلات، توجيه المهام، اتفاقيات مستوى الخدمة، التصعيد، التوقيع الإلكتروني/PKI/HSM، إدارة المستندات، وتدقيق شامل.
  - التقنية: خدمات .NET، واجهات مصغّرة، gRPC، أحداث Kafka، بحث نصّي OpenSearch، مخزن مستندات متوافق مع S3.

- نظام إدارة الموارد البشرية (HRMS)
  - بيانات الموظّفين، التوظيف والانضمام، مواءمة الرواتب، الإجازات/الدوام، الأداء، الخدمة الذاتية؛ متعدد المستأجرين مع توطين وضوابط وصول قوية.
  - التقنية: خدمات .NET مصغّرة، واجهات مصغّرة بـ Next.js، PostgreSQL، Redis، RabbitMQ؛ OIDC؛ واجهة GraphQL.

- إدارة المستندات والسجلات الإلكترونية (EDRMS)
  - إدخال، OCR/تصنيف، سياسات الاحتفاظ والحجز القانوني، الإصدارات، التحكم بالوصول، التعاون، نسخ احتياطية آمنة، مشاركة Zero‑Trust؛ بحث متجهي.
  - التقنية: OpenSearch/Elasticsearch، تخزين S3 متوافق، خطوط فهرسة Kafka، خدمات .NET/Node.js، واجهات مصغّرة بـ Next.js.

- المراسلة والإشعارات متعددة القنوات
  - SMS، بريد إلكتروني، Push، داخل التطبيق؛ قوالب وتوطين؛ تحديد المعدّل، إيصالات التسليم، تجاوز الفشل متعدد المزوّدين؛ Webhooks وأحداث.
  - التقنية: خدمات Node.js، Kafka/RabbitMQ، Webhooks REST، OIDC، OpenTelemetry.

- مركز التكامل وبوابة API
  - موصلات لـ ERP/CRM/Tax؛ واجهات REST/GraphQL؛ جسر gRPC؛ التقاط تغيّر البيانات Debezium؛ تحويلات وجدولة؛ إدارة أسرار؛ شبكة خدمات.
  - التقنية: بوابة API، اتحاد GraphQL، بروكسي gRPC، Kafka، PostgreSQL، Vault، Istio/Linkerd.

- أساس البيانات والتحليلات
  - تقارير تشغيلية، خطوط شبه آنية، وجهات مادية، مخارج BI، فهرس بيانات وتتبع نسب؛ خطوط CDC من الأنظمة المصدر.
  - التقنية: Kafka Streams، PostgreSQL، OpenSearch، تخزين كائني.

- وحدات اختيارية وبحث وتطوير (افتراضي)
  - نماذج مدعومة بالذكاء الاصطناعي لاستخراج النماذج/المستندات، بحث RAG فوق الأرشيفات، كشف الشذوذ للأحداث المالية، مكتب مساعدة حواري.
  - التقنية: قواعد بيانات متجهة، خطوط تضمين، نماذج داخلية/سحابة خاصة، برمجيات حوكمة/حواجز، خصوصية حسب التصميم.

## مشاريع ممثّلة
- تطبيق «بيستي» — أحداث، رسائل، تذاكر، مراسلات، ودفع فواتير.
  - التقنية: React Native + بوابة ويب (Next.js)، خدمات مصغّرة NestJS (Node.js)، gRPC داخلي + REST/GraphQL خارجي، PostgreSQL، Redis؛ Docker/Kubernetes؛ OIDC؛ OpenTelemetry.

- «دكتور سازه» — منصة تفتيش المباني والتقييم الهندسي.
  - التقنية: Next.js (React + TypeScript) كواجهات مصغّرة، خدمات مصغّرة NestJS، gRPC + بوابة REST، PostgreSQL، OpenSearch، تخزين متوافق مع S3؛ CI/CD عبر GitHub Actions.

- مصمّم نماذج فروع بنك ملت (RISAPP) — سير عمل مصرفي وتصميم منخفض الكود.
  - التقنية: واجهات مصغّرة (Next.js)، خدمات .NET مصغّرة + gRPC، بوابة REST/OpenAPI، Kafka، MongoDB (تعريفات النماذج)، PostgreSQL (تعاملات)، Redis؛ Kubernetes مع Helm/Kustomize.

- إدارة الموارد البشرية — بريد إيران
  - التقنية: خدمات .NET مصغّرة (Minimal APIs)، gRPC داخلي، واجهات مصغّرة Next.js، PostgreSQL، RabbitMQ، صلاحيات RBAC/ABAC مع Keycloak (OIDC)، لوحات عبر Grafana.

- مستندات المحاسبة — منظمة نظام المهندسين (TCEO)
  - التقنية: خدمات .NET، معالجة مدفوعة بالأحداث (Kafka)، PostgreSQL، مخارج OLAP/BI، سجلات تدقيق وغير قابلة للتغيير؛ مراقبة عبر OpenTelemetry + Prometheus/Grafana.

- الأتمتة الإدارية — سكك حديد الجمهورية الإسلامية الإيرانية
  - التقنية: واجهات مصغّرة (Next.js)، خدمات .NET مصغّرة، gRPC بين الخدمات، Elasticsearch للبحث النصي/الوثائقي، مخزن مستندات متوافق مع S3، Keycloak للمصادقة الموحدة OIDC؛ نشر متعدد البيئات على Kubernetes.

## ممارسات هندسية
- العمارة: خدمات معيارية، حدود واضحة، تصميم API‑First؛ واجهات أمامية SPA مع عقود مTyped عند الحاجة.
- الجودة: اختبارات مؤتمتة، مراجعات كود، تحليل ساكن، CI لبُنى قابلة للإعادة.
- التسليم: إصدارات تدريجية، تماثل البيئات، نشر قابل للملاحظة.
- الأمن: RBAC/ABAC، أقل امتياز، تتبع وتدقيق، ممارسات ترميز آمن.
- القابلية للملاحظة: سجلات مهيكلة وقياسات قابلة للتنفيذ.

## مصفوفة التقنية
- المفضّل (البناءات الجديدة)
  - Backend: .NET (ASP.NET Core), C#; Node.js (NestJS/Express)
  - APIs: REST (OpenAPI), GraphQL, gRPC, WebSocket
  - Frontend: React + TypeScript; Next.js (App Router), Vite
  - UI: Tailwind CSS, Material UI; Design Tokens, Storybook
  - State/Data: React Query/RTK Query; React Hook Form; Zod
  - Mobile: React Native (TypeScript)
  - Data: PostgreSQL, SQL Server, MongoDB; Redis
  - Search/Analytics: OpenSearch/Elasticsearch; BI Exports
  - Messaging: Kafka (events), RabbitMQ (queues)
  - AuthN/Z: OIDC/OAuth2, JWT, RBAC/ABAC
  - DevOps: Docker, Kubernetes, GitHub Actions; Helm/Kustomize; Terraform (IaC)
  - Observability: OpenTelemetry, Prometheus, Grafana, ELK/OpenSearch

- المدعوم (الأنظمة الحالية)
  - ASP.NET (Full Framework), HTML/CSS/Bootstrap
  - Node.js + React, Material UI
  - SQL Server; REST Web Services; SMS Gateways

## التواصل
- موقع ويب: https://rismun.ir
- البريد: info@rismun.ir
- العنوان: شارع ولي‌عصر، رقم 2361، طهران، إيران
- الهاتف: ‎+98 21 88178400 ، ‎+98 21 88178500
- الفاكس: ‎+98 21 88178500
- الساعات: السبت–الأربعاء 09:00–17:00 (الخميس/الجمعة عطلة)

## الشبكات الاجتماعية
- GitHub: https://github.com/rismun
- Instagram: https://www.instagram.com/rismuntech/
- Facebook: https://facebook.com/rismunco
- Twitter: https://twitter.com/rismunco

<p align="center">
  <a href="README.md">English</a> · <a href="README.fa.md">فارسی</a>
</p>

