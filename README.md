# Lyrid Golang 1.x Gin Template

## SAMPLE TEMPLATE
![hi](/dist/assets/img/lyrid_logo_large.png)
This template is for _language_ suitable for uploading to the Lyrid Platform.

## Prerequisites 
1. Register an account at [Lyrid Web Application](https://app.beta.lyrid.io/) 
2. Download our command line tool, [the lc](https://docs.lyrid.io/initialization)
3. Clone the repo 'git clone https://github.com/sample_here'

## Run locally with:
```
go get
go run ./main.go
```
Open http://localhost:8000

## Edit the names (optional):
Open .lyrid-definition and change the App and Module name, because this will override another applications with the same name in the platform.

## User can clone this repo, then Replace these variables in all files :
- YOUR_APP_NAME
- YOUR_MODULE_NAME
- YOUR_FUNCTION_NAME

To change your file information:
Open ```.lyrid-definition.YML``` file
Change ```name``` and ```module name``` to your choice and save.

### Start Coding!
Users can edit route url, settings, and views with custom APIs. 

### Submit to Lyrid 
Use our command line tool to easily upload your application to the cloud.
```
lc code submit
```

## Contact Us
Have any questions? We are here to help!
Email us at support@lyrid.io  

### Find us on social medias
- [Discord](https://discord.com/invite/xtCCtc9WAX)
- [LinkedIn](https://www.linkedin.com/company/lyrid/?viewAsMember=true)
- [Twitter](https://twitter.com/LyridInc)
- [Facebook](https://www.facebook.com/lyridinc)

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/Gin-Go1.x-Template.git&env=empty&project-type=Gin-Go1.x&repo-name=Gin-Go1.x-Template">
  <button>
    <img src="/dist/assets/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>
