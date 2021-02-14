<h1 align="center">Face Scan</h1>
<p align="center">
  <a href="https://github.com/DanielLechner/FaceScan/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/DanielLechner/FaceScan"></a>
  <a href="https://github.com/DanielLechner/FaceScan/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/DanielLechner/FaceScan"></a>
  <a href="https://github.com/DanielLechner/FaceScan/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/DanielLechner/FaceScan"></a>
  <a href="https://github.com/DanielLechner/FaceScan/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/DanielLechner/FaceScan"></a>
</p>
<p align="center">
FaceScan is a Python script which can detect Face Masks in webcams, images, video files and streams
</p>

## ✨ Demo
#### 📹 Webcam
`FaceScan` is able to detect Face Masks in video feed from connected webcams in realtime:


#### 📁 Files
`FaceScan` is able to detect Face Masks locally saved video and images files:

<table style="width:100%">
    <tr>
      <td><p>Before</p></td>
      <td><p>After</p></td>
    </tr>
    <tr>
        <td><img src="https://github.com/DanielLechner/FaceScan/blob/main/readme/before_images/7.jpg"></td>
        <td><img src="https://github.com/DanielLechner/FaceScan/blob/main/readme/after_images/7.jpg"></td>
    </tr>
  <tr>
        <td><img src="https://github.com/DanielLechner/FaceScan/blob/main/readme/before_images/12.jpg"></td>
        <td><img src="https://github.com/DanielLechner/FaceScan/blob/main/readme/after_images/12.jpg"></td>
    </tr>
</table>

#### 📲 Online Streams
`FaceScan` is able to detect Face Masks in online Streams such as rtsp, 

## ⚙️ Intallation

Clone git repo locally
```bash
$ git clone https://github.com/DanielLechner/FaceScan
```

Change directory to FaceScan/app
```bash
$ cd FaceScan/app
```

Intstall all dependencies from [requirements.txt](https://github.com/DanielLechner/FaceScan/blob/main/app/requirements.txt)
```bash
$ pip install -r requirements.txt
```

Enviroment should now be fully functional

## 🚀 Usage

As mentioned above, there are many ways to use our Python program. Here you can check all the functions:

```bash
$ python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa  # rtsp stream
                            rtmp://192.168.1.105/live/test  # rtmp stream
                            http://112.50.243.8/PLTV/88888888/224/3221225900/1.m3u8  # http stream

```

## 👨🏾‍💻👨🏻‍💻 Code Contributors


## ✍🏾 Authors


## 📝 License
