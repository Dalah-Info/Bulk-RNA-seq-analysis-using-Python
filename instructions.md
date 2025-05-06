


# 📊 ورشة عمل: تحليل بيانات Bulk RNA-seq باستخدام لغة برمجة بايثون

مرحبًا بكم في صفحة التحضير لورشة العمل!
<br>
لضمان تجربة تعليمية سلسة، نرجو منكم اتباع الخطوات التالية قبل الحضور، حيث أنه لن يتم شرحها أثناء ورشة العمل.

## قيم مستوى معرفتك لتحديد قائمة المهام المطلوبة:
* إذا كنت قد عملت سابقا على: Python, Jupyter Notebook, Conda. الرجال الإنتقال إلى [قائمة المهام 2 مباشرة](#قائمة-المهام-2).
* إذا لم تعمل سابقا على أي من المذكور سابقا، فابدأ من [قائمة المهام 1](#قائمة-المهام-1).

<br>
<br>
<br>

---


  
## قائمة المهام 1:
* تثبيت Conda. يمكنك مشاهدة فيديو مفصل لطريقة التثبيت [هنا](https://www.youtube.com/watch?v=GWKlRmuf_Iw&t=291s).
* تثبيت pip. يمكنك مشاهدة فيديو مفصل لطريقة التثبيت [هنا](https://www.youtube.com/watch?v=qpdzT5SmLws).
* تثبيت بايثون و Jupyter Notebook. يمكنك مشاهدة فيديو مفصل لطريقة التثبيت [هنا](https://www.youtube.com/watch?v=WS5f18CncCo&t=1s).

<br>

---


## قائمة المهام 2:
  * باستخدام conda. يُفضل إنشاء بيئة عمل جديدة لتثبيت الحزم المطلوبة:
```bash
conda create -n rnaseq python=3.11
conda activate bulk-rnaseq
```
* تثبيت الحزم التالية (انسخ الكود مباشرة):
```bash
pip install numpy pandas pydeseq2 scanpy scikit-learn matplotlib seaborn plotly sanbomics mygene gseapy notebook
```


  
<br>
<br>
<br>

---

  

