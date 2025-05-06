📊 ورشة عمل: تحليل بيانات Bulk RNA-seq باستخدام لغة برمجة بايثون
مرحبًا بكم في صفحة التحضير لورشة العمل!
لضمان تجربة تعليمية سلسة، نرجو منكم اتباع الخطوات التالية قبل الحضور.

✅ قائمة التحقق
🔹 هل لديك بايثون مثبت على جهازك؟
🔹 هل لديك Anaconda مثبت على جهازك؟
🟢 في حال كانت الإجابة "نعم":
افتح الـ Terminal (أو Anaconda Prompt في ويندوز)

أنشئ بيئة conda جديدة:

bash
Copy
Edit
conda create -n bulk-rnaseq python=3.10
فعّل البيئة:

bash
Copy
Edit
conda activate bulk-rnaseq
ثبّت الحزم المطلوبة:

bash
Copy
Edit
pip install numpy pandas pydeseq2 scanpy scikit-learn matplotlib seaborn plotly sanbomics mygene gseapy notebook
🔴 في حال كانت الإجابة "لا":
1. ثبّت بايثون وAnaconda:
شاهد هذا الفيديو الذي يشرح الخطوات خطوة بخطوة:
🎥 رابط يوتيوب لتثبيت بايثون وأناكوندا

2. بعد التثبيت، اتبع الخطوات التالية:
افتح Anaconda Prompt أو الـ Terminal

أنشئ بيئة جديدة:

bash
Copy
Edit
conda create -n bulk-rnaseq python=3.10
فعّل البيئة:

bash
Copy
Edit
conda activate bulk-rnaseq
ثبّت الحزم المطلوبة:

bash
Copy
Edit
pip install numpy pandas pydeseq2 scanpy scikit-learn matplotlib seaborn plotly sanbomics mygene gseapy notebook
