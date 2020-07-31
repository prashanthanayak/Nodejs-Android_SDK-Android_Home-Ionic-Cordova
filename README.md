## Initially install nodejs
curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -
sudo apt-get install -y nodejs

## Install openjdk
sudo apt-get install openjdk-8-jdk

## Install android sdk and extract to home page
wget http://dl.google.com/android/android-sdk_r24.2-linux.tgz

## Install the sdk packages required
sudo android-sdk-linux/tools/android

## To set ANDROID_HOME path Add below line at the end of ~/.bashrc
export ANDROID_HOME=/home/user_name/android-sdk-linux

## Install cordova and ionic
npm install -g cordova ionic

## Good to go...
