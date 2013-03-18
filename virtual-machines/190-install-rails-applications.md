## 190 Install Rails Applications


### Initialize Production Directory and Permissions

```console
cd /usr/local
sudo mkdir production
sudo chgrp rvm production
sudo chmod 775 production
```

### Installing MySQL Library to allow compilation of mysql2 ruby gem

```console
sudo yum install mysql mysql-devel
```

### Installing libraries to allow compilation of nokogiri gem

```console
sudo yum install libxml libxml-devel libxslt libxslt-devel
```

### Install individual Ruby on Rails Applications

* [Sleep Portal](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/410-install-sleep-portal.md)
* [Task Tracker](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/420-install-task-tracker.md)
* [CHAT Publications](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/430-install-chat-publications.md)
* [Screen](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/440-install-screen.md)
* [Slice](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/450-install-slice.md)
* [Training Grant](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/460-install-training-grant.md)
* [Rely](https://github.com/sleepepi/sleepepi/tree/master/rails-applications/470-install-rely.md)