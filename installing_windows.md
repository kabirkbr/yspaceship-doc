## Installing on Windows

1. Install [Docker for Windows 10 Pro](https://download.docker.com/win/stable/InstallDocker.msi) or follow [instructions](https://docs.docker.com/docker-for-windows/);

1. Share local disk to Docker container as explained [here](https://rominirani.com/docker-on-windows-mounting-host-directories-d96f3f056a2c#.vi1t2jpco). You may need to set user password in order for this to work -- see [here](https://www.tenforums.com/tutorials/5239-password-user-account-change-windows-10-a.html) in such case. Force Windows skip login screen by following [this](https://www.windows10forums.com/threads/how-to-disable-login-screen-on-win-10.165/), if preferred.

1. Allow PowerShell to run unsigned scripts by opening PowerShell with 'Run as Administrator' mode and running `Set-ExecutionPolicy unrestricted` command;

1. Install [PDF-X-Change](https://www.tracker-software.com/product/pdf-xchange-editor) and (optionally but preferably) set it as a default PDF reader;

1. Download the [ySpaceShip start/stop script](https://bitbucket.org/vveitas/yspaceship/raw/master/scripts/yspaceship.ps1) and place it in a place with at least 2-3 GB of space (preferably more);

1. If you do  not like to operate via cmd or powershell, download [launch](https://bitbucket.org/vveitas/yspaceship/raw/master/scripts/ySpaceShip%20LAUNCH.lnk) and [stop](https://bitbucket.org/vveitas/yspaceship/raw/master/scripts/ySpaceShip%20STOP.lnk) links and place them on Desktop. Correct the directory of script in both (according to step 3);

1. Double-click on LAUNCH link and see what happens...
