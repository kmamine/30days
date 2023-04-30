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

## **Activate the conda environment**

To use a conda environment that we had just created that is named `stenv`, enter the following into the command line:

```bash
conda activate stenv
```

## **Install the Streamlit library**

It's now time to install the `streamlit` library:
```bash
pip install streamlit
```

## **Launching the Streamlit demo app**
To launch the Streamlit demo app (Figure 1) type:
```bash
streamlit hello
```
