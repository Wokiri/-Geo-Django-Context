# <p align='center'>**CONTEXTUALIZING (GEO)DJANGO**</p>
## <p>**Concepts about [Django](https://docs.djangoproject.com/en/3.1/) and [GeoDjango.](https://docs.djangoproject.com/en/3.1/ref/contrib/gis/)**</p>

<br/>

> **"Django: The Web Framework For Perfectionists With Deadlines"** Django


> **"GeoDjango: A world-class geographic Web framework."** GeoDjango

<br/>

<p align='center'><img src="https://dub01pap001files.storage.live.com/y4mC1fFUTSExyTKlOT3fXLEkrSiflRH9ZIb-nc-iugS-_bFH1sRsYl1YNo_pPm8_fM_bbfF2qXrDJSojYE2FBULifFy82R3o1cd8kjP8P6D9TKplsdtVS3OGykBBuGY7iOmuQZsVFKD2MrfMpA5ZOrThIKLX-FC-fENIvu_4DGZ3aNfLIhkQ8EuTEr-9IOR0yn5?width=1440&height=1920&cropmode=none" width="1440"/>&nbsp;&nbsp;</p>

<br/>

### Prepared by: [@JWokiri](https://twitter.com/JWokiri). <br/>

---
<br/>

## Repo Overview <br/>
I try to give context to the various use case scenerios in using Django and GeoDjango; mainly through visualized graphics, a littlebit of code and some explanations.

Django is a high-level python web framework that encourages rapid development and clean, pragmatic design of web apps.


---
<br/>

## **Minimum Requirement**

The **`Minimum Requirement`** for practically working with Django is Python (prefferably version > 3), because it is a Python Web framework.

NOTE the following python versions with their respective supported Django versions:

| Python versions | Django version |
| :---------------| :-------------:|
| 2.7, 3.4, 3.5, 3.6, 3.7 (added in 1.11.17) | 1.11 |
| 3.4, 3.5, 3.6, 3.7 | 2.0 |
| 3.5, 3.6, 3.7 | 2.1 |
| 3.5, 3.6, 3.7, 3.8 (added in 2.2.8) | 2.2 |
| 3.6, 3.7, 3.8 | 3.0, 3.1 |


<br/>

## Time to dive in...

<br/>

## <p align='center'>1. Ensure you have python installed.</p>

This may be confirmed by verifying the version. Type python --version from your shell (command prompt or powershell-- henceforth I will refer to either as *terminal*):

``` powershell
python --version
```

If you see the version displayed...

```powershell
Python 3.8.6
```

good!

If you do not have python installed, please do so from [the official download website](https://www.python.org/downloads/).

<br/>

## <p align='center'>1. Make a virtual environment.</p>


A virtual environment has its own Python binary (which matches the version of the binary that was used to create this environment) and can have its own independent set of installed Python packages in its site directories.

This is important in the sense that the installed packages for each virtual environment don’t interfere with each other, or, it prevents installed packages from affecting system services and other users of the machine.


With python3 installed, a new virtual environment can then be created by running:

``` bash
python -m venv ./venv386
```
This will create a directory within the present one called *venv386* with a copy of the python executable amongst other files into it.

`NB` the **-m** in this command means venv is located on the Python module path and is run as a script.

<br/>

## <p align='center'>2. Activating the virtual environment.</p>

This done by running the following into the terminal (for windows):

``` bash
./venv386/Scripts/activate
```

<br/>

## <p align='center'>3. Installaations.</p>

Within an activated virtual environment, install Django by running:

``` bash
python -m pip install django
```
All packages installed within this environment will be isolated from other environments and system wide packages.


<br/><br/><br/>

## **to be continued...**