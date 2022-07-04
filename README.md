# Timer

Simple app to help protect your eyes. According to optometrists in order to save your eyes, you should follow the 20/20/20. 
It means you should to rest your eyes every 20 minutes for 20 seconds by looking more than 20 feet away.

**Built with Electron**

After cloning files use ` yarn install ` to install dependencies.

In terminal use ` yarn start ` to start the aplication.

Interval is set to ` 50 ` for easy testing. If you want to use it as a proper timer go to ` const startTimer ` and change ` setInterval ` parameter from 50 to 1000.

App will countdown from 20 minutes to 0 - this should be your work time. After that it will play a sound and  switch to "rest" mode with a countdown of 20 seconds - this is when you should think about your eyes and how to care about them ;).
