Swift Recon Nagios checks
=========================

A set of python scripts which call swift-recon (see http://swift.openstack.org), parse the output and return results to nagios.

They can be called by a remote nagios with either check_by_sms or check_nrpe.

You can tell check_diskusage.py your thresholds of when to alert - run check_diskusage.py --help for options.
