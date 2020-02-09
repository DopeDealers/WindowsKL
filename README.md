# WindowsKL
windows KL is a fork of sharplocker. all rights to Pickfordmatt

WindowsKL helps get current user credentials by popping a fake Windows lock screen, all output is sent to a webserver of your choice i.e requestbin or a personal website. It is written in C# to allow for direct execution via memory injection using techniques such as execute-assembly found in Cobalt Strike or others, this method prevents the executable from ever touching disk. It is NOT intended to be compilled and run locally on a device. 

## Works
* Single/Multiple Monitors
* Windows 10
* Main monitor needs to be 1080p otherwise the location of the elements are wrong

## How to
* Compile WindowsKL from source via VisualStudio etc
* Within a Cobalt Strike implant run execute-assembly C:/{location of exe}
* Pray and wait for creds
