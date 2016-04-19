argo-ncg-eudat
==============

This package contains the Nagios specific configuration generator for 
the Nagios Grid Service Monitor.


Usage
=====

```sh
$ ncg.pl --help
```

Nagios configuration generator

    Options:
        --config STRING
            Path to generated configuration file.
            For detailed description of options for
            individual modules see perldoc.
            (default: /etc/ncg/ncg.conf)

        -h, --help
            Basic program description

        -v, --verbose
            Print verbose logging information

        -d, --debug
            Print detailed program execution flow

For detailed information on config file check perldoc of individual module. For example:

    perldoc /usr/lib/perl5/vendor_perl/5.8.5/NCG/ConfigGen/Nagios.pm

Variables are described in section "new".


