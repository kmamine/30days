# إعداد بيئة تطوير محلية

قبل أن نبدأ فعليًا في إنشاء تطبيقات Streamlit ، سيتعين علينا أولاً إعداد بيئة تطوير.

لنبدأ بتثبيت وإعداد بيئة conda.

## **تثبيت نظام conda**
- قم بتنزيل وتثبيت conda من خلال الانتقال إلى https://docs.conda.io/en/latest/miniconda.html واختيار نظام التشغيل الخاص بك (Windows، Mac أو Linux).
- ثمّ قم بتشغيل المثبّت لتثبيت conda.


## **إنشاء بيئة تطويرية جديدة في conda**
الآن بعد تثبيت `conda` ، دعنا نقوم بإنشاء بيئة `conda` لإدارة جميع تبعيات مكتبات Python.

لإنشاء بيئة جديدة باستخدام Python 3.9 ، قم بإدخال التالي:

```bash
conda create -n stenv python=3.9
```
حيث `create -n stenv` سيقوم بإنشاء بيئة `conda` بإسم `stenv`، و `python=3.9` سيقوم بتثبيت Python بالإصدار 3.9 في البيئة التي تم إنشائها.

## **تفعيل بيئة conda**

لكي تستخدم بيئة conda التي قمنا بإنشائها واسمها `stenv`، أدخل الأمر التالي في سطر الأوامر:


```bash
conda activate stenv
```

## **قم بتثبيت مكتبة Streamlit في البيئة الافتراضية**

حان الآن وقت تثبيت مكتبة streamlit:
```bash
pip install streamlit
```

## **Launching the Streamlit demo app**
To launch the Streamlit demo app (Figure 1) type:
```bash
streamlit hello
```
