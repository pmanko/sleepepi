# sleepepi proxy configuration and server setup

Documentation providing architecture overview of sleepepi

## Network Architecture

```
`-- sleepepi.partners.org
    `-- sleepepi.dipr.partners.org          1GB     CentOS release 5.7 (Final)
        |-- epista01.dipr.partners.org      1GB     CentOS release 6.3 (Final)
        |-- ...
        |-- epipro01.dipr.partners.org      1GB     CentOS release 5.8 (Final)
        |-- epipro02.dipr.partners.org      1GB     CentOS release 5.8 (Final)
        |-- ...
        `-- epiproXX.dipr.partners.org      ...     ...
`-- slice.partners.org
    `-- slice.dipr.partners.org             1GB     CentOS release 6.3 (Final)
`-- tasktracker.partners.org
    `-- tasktracker.dipr.partners.org       1GB     CentOS release 6.2 (Final)
```

## Server Responsibilities

Primary Frontend Server

- [sleepepi.dipr.partners.org](https://github.com/sleepepi/sleepepi/tree/master/virtual-machines/000-sleepepi.dipr.partners.org.md)

Production Application Servers

- [epiproXX.dipr.partners.org](https://github.com/sleepepi/sleepepi/tree/master/virtual-machines/100-epiproXX.dipr.partners.org.md)

Staging Application Servers

- [epistaXX.dipr.partners.org](https://github.com/sleepepi/sleepepi/tree/master/virtual-machines/200-epistaXX.dipr.partners.org.md)

Demo Servers

- [tasktracker.dipr.partners.org](https://github.com/sleepepi/sleepepi/tree/master/virtual-machines/300-tasktracker.dipr.partners.org.md)

- [slice.dipr.partners.org](https://github.com/sleepepi/sleepepi/tree/master/virtual-machines/400-slice.dipr.partners.org.md)