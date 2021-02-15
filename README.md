# <p align='center'>**CONTEXTUALIZING (GEO)DJANGO**</p>
## <p>**Concepts about [Django](https://docs.djangoproject.com/en/3.1/) and [GeoDjango.](https://docs.djangoproject.com/en/3.1/ref/contrib/gis/)**</p>

<br/>

> **"Django: The Web Framework For Perfectionists With Deadlines"** Django


> **"GeoDjango: A world-class geographic Web framework."** GeoDjango

<br/>

<p align='center'><img src="https://dub01pap001files.storage.live.com/y4mC1fFUTSExyTKlOT3fXLEkrSiflRH9ZIb-nc-iugS-_bFH1sRsYl1YNo_pPm8_fM_bbfF2qXrDJSojYE2FBULifFy82R3o1cd8kjP8P6D9TKplsdtVS3OGykBBuGY7iOmuQZsVFKD2MrfMpA5ZOrThIKLX-FC-fENIvu_4DGZ3aNfLIhkQ8EuTEr-9IOR0yn5?width=1440&height=1920&cropmode=none" width="1440"/></p>

&nbsp;&nbsp;<br/>

### Prepared by: [@JWokiri](https://twitter.com/JWokiri). <br/>

---
<br/>

## Repo Overview <br/>
I try to give context to the various use case scenerios in using Django and GeoDjango; mainly through explanations, ocassionally through visualized graphics, and bits of working code.


### `What then is Django?`
Django is a high-level python web framework.

To a developer, it encourages rapid development and clean, pragmatic design of web apps.

It serves users' needs by availing feature-rich functionalities including an admin panel for administrators amongst other utilities that leaves user' well attended to.

<p align='center'><img src="https://dub01pap001files.storage.live.com/y4mqxFLrBqQh2vZnijft8GG9F9k9UVWTa9jrZ2Kwpo2VgWSET2H-3sO3bB_zxFaiVu8XyWzI0wKDp3sM3zyuZarqEFgoKTg2ZnX11A-g4NN6wZS2z5-tEbfCN1WjNh6kunGKO_tTvQXXnqFg1PmsP90I0UlJAhx15pFhHmKb9lefqOE782FhXyYpLKy7ReW9iyU?width=1440&height=1920&cropmode=none" width="1440"/></p>

<br/>

### `At the core of the matter` django understands what a user is requesting from some remote server and responds to that request by serving some sort of resource which may be a webpage, a video, a document, an image, e.t.c.


<p align='center'><img src="https://dub01pap001files.storage.live.com/y4mAke6bIYCf7qshEBnUoi07qawxu_yxAs_-4-avpatrZiwBGbgMhC99E9IseD7CBV5T5mq9zK_XxjU_8KH5G6GXEhyscI3VJ4I--yzreVF9PqQRWVF4z0pMrgW-HlzKUIITuZ2Dl-ViritKryG2AKKozqw45qkNKkTaTtuMQXqVRvM8Q4jvABorpGQjMw0CD9v?width=1920&height=1440&cropmode=none" width="1920"/></p>

<br/>


<p align='center'><img src="https://dub01pap001files.storage.live.com/y4mBXTSqdjrgdI8iftoGO6mY8aKLmZCCKpMZa8DGGpcOEAbZTTH5pYNjtkkMUnJ4IIf2hrn4xhgoZ2FzHsePjWzX9cDSinlPT0RTfe2kVhrEMJ6qUeVSyhmCWeTieW7zMdOMz5JbiwigmMQdhlF-jolS8NQMkJJymU43VUXnaUyicx9qnToBe6tZAV22v3T1ng9?width=1920&height=1440&cropmode=none" width="1920"/></p>

<br/>


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

## <p align='center'>1. Install a Database</p>

This I highly recommend: You see the reason you want to use django is to serve dynamic content whereby resource objects are stored in a database.


<br/>


## <p align='center'>2. Ensure you have python installed.</p>

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

## <p align='center'>3. Make a virtual environment.</p>


A virtual environment has its own Python binary (which matches the version of the binary that was used to create this environment) and can have its own independent set of installed Python packages in its site directories.

This is important in the sense that the installed packages for each virtual environment don’t interfere with each other, or, it prevents installed packages from affecting system services and other users of the machine.


With python3 installed, a new virtual environment can then be created by running:

``` bash
python -m venv ./venv386
```
This will create a directory within the present one called *venv386* with a copy of the python executable amongst other files into it.

`NB` the **-m** in this command means venv is located on the Python module path and is run as a script.

<br/>

## <p align='center'>4. Activating the virtual environment.</p>

This done by running the following into the terminal (for windows):

``` bash
./venv386/Scripts/activate
```

<br/>

## <p align='center'>5. Package Installations.</p>

Within an activated virtual environment, install Django by running:

``` bash
python -m pip install django
```
All packages installed within this environment will be isolated from other environments and system wide packages.


<br/><br/><br/>

## **to be continued...**