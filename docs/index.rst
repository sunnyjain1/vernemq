.. VerneMQ documentation master file, created by
   sphinx-quickstart on Tue Oct 14 16:46:48 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

VerneMQ: A Distributed MQTT Broker
==================================

Release v\ |version|. (:ref:`Installation <install>`)

VerneMQ is an :ref:`Apache2 licensed <apache2>` distributed `MQTT <http://www.mqtt.org>`_ broker, developed in `Erlang <http://www.erlang.org>`_.

MQTT stands for MQ Telemetry Transport. It is an extremely simple and lightweight publish/subscribe messaging protocol, that was invented at IBM and Arcom (now Eurotech) to connect restricted devices in low bandwidth, high-latency or unreliable networks.

VerneMQ implements the MQTT 3.1 and 3.1.1 specifications, integration of MQTT-SN is planned. Currently are following features implemented:

* QoS 0, QoS 1, QoS 2
* Basic Authentication and Authorization 
* Bridge Support
* $SYS Tree for monitoring and reporting
* SSL Encryption
* Dynamic Topics
* Websockets Support
* Cluster Support
* Scriptable via Lua 
* SNMP Monitoring
* Logging (Console, Files, Syslog)
* Reporting to Graphite and CollectD

**Although VerneMQ hasn't reached version 1.0.0 yet, it is already deployed in small to medium size projects. Erlio GmbH, the main company sponsor behind the VerneMQ development provides commercial services around VerneMQ, namely M2M consulting, VerneMQ extension development, and service level agreements.** 

VerneMQ can be deployed on most platforms where a recent Erlang version (R16B or higher) is available. Software packages for Redhat/Fedora (and variants), Debian/Ubuntu (and variants), FreeBSD, OSX, SmartOS, and Solaris will be provided. Please follow the :doc:`Installation <install>` instructions.

**The automated packaging is not yet ready, but the packages can be simply generated on the target system following the** :ref:`packaging instructions <packaging>`

User Guide
----------

.. toctree::
    :maxdepth: 3

    install
    start
    configure
    open_files_limit
