![GoIndex](https://raw.githubusercontent.com/dhlalit11/goindex/master/themes/logo.png)  
  
GoIndex  
====  
Google Drive Directory Index  
Combining the power of [Cloudflare Workers](https://workers.cloudflare.com/) and [Google Drive](https://www.google.com/drive/) will allow you to index you files on the browser on Cloudflare Workers.    

## Huge Thanks to [Donwa](https://github.com/donwa) for making this index
`index.js` is the content of the Workers script.  

## Demo
Here's the link to [Classic](http://classic.fwilso.workers.dev) Index Sample.

Here's the link to  [Material](http://material.fwilso.workers.dev) Index Sample.

## Deployment  
1.Install `rclone` software locally  
2.Follow [https://rclone.org/drive/]( https://rclone.org/drive/) bind a drive  
3.Execute the command`rclone config file` to find the file `rclone.conf` path  
4.Open `rclone.conf`,find the configuration `root_folder_id` and `refresh_token`  
5.Download index.js in https://github.com/dhlalit11/goindex and fill in root and refresh_token  
6.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)

## Quick Deployment  
No Quick Deployment feature yet

## About  
Cloudflare Workers allow you to write JavaScript which runs on all of Cloudflare's 150+ global data centers.  
