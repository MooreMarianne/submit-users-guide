Monitoring at submit
--------------------

.. tags:: Slurm, Condor

This section will detail the monitoring available at submit. Here we will detail how you can keep track of the submit machines as you work as well as monitor your condor jobs.

The main submit page
~~~~~~~~~~~~~~~~~~~~

On the main `submit page <http://submit.mit.edu/>`_ you can find interesting links useful for monitoring. Most of these links are explained in more detail below.

Ganglia Monitoring for submit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ganglia is a distributed monitoring system for high-performance computing systems such as submit. The Ganglia monitoring can be found through a link on the main submit page or can be found directly `here <http://submit08.mit.edu/ganglia/>`_. Information on the individual servers can be found at the bottom of the page or through the following `link to servers <http://submit08.mit.edu/ganglia/?c=Submits>`_.

CondorMon
~~~~~~~~~

If you would like to monitor your condor jobs you can use the condor monitoring `CondorMon <https://submit.mit.edu/condormon/index.html>`_, where you can see how many condor jobs are running, idle or held as well as where they are being submitted to. This site also gives an overview of your recent submissions.

The submissions that are sent to the CMS global pool can also be monitored through the central site `CERN Summary <https://cms-gwmsmon.cern.ch/institutionalview/T2_US_MIT>`_.

SlurmMon
~~~~~~~~

To monitor your slurm jobs you can use the slurm monitoring `SlurmMon <https://submit.mit.edu/slurmmon/index.html>`_, where you can see how many slurm jobs are running, as well as where they are being submitted to. This site also gives an overview of your recent submissions including submissions to the LQCD cluster and submissions to GPU machines.

Summary Plots for SubMIT
~~~~~~~~~~~~~~~~~~~~~~~~

There are additional summary plots to help keep track of the growth and health of the SubMIT system `Submit Monitoring Tools <http://submit.mit.edu/home_monitor/index.php>`_. 

Monitoring for the T3
~~~~~~~~~~~~~~~~~~~~~

For those working on the T3 machines, we have similar `monitoring  <http://t3serv001.mit.edu/>`_, including `T3 CondorMon <http://t3serv007.mit.edu/condormon/>`_ and `Ganglia <http://t3serv001.mit.edu/ganglia/>`_.
