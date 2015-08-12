# Jenkins Maintenance Mode Plugin

Ever need to restart Jenkins but there is a 4 hour job 50% complete?
You could come back in 2 hours when it should be finished only to find out that another long running job has been started.
Otherwise you can enable safe shutdown mode to allow the current jobs to finished, but then Jenkins is sitting for 2 hours when it could easily fit in a lot of 10 minute jobs.

The Maintenance mode Plugin provides the following functionality.

Enable Maintnenace mode to stop any new jobs starting.
Notification text which is displayed at the top of the Jenkins page to inform users.
Allow jobs to run if they 'should' be finished by a specified time - using Jenkins estimated time to completion.
Allow jobs which have been marked as maintenance Jobs to run.
