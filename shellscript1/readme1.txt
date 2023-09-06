*************************************************

1)create directory for our mission
   $mkdir lunar-mission

2)for that mission we created arocket
   $rocket-add lunar-mission

3)now should follow launch sequence by running cmds
   $rocket-start-power lunar-mission
   $rocket-internal-power lunar-mission
   $rocket-start-sequence lunar-mission
   $rocket-start-engine lunar-mission
   $rocket-lift-off lunar-mission

4)finally we tetsted the status 
   $rocket-status unar-mission

************************************************



************************************************************************

now to perform all this task in shellscript we create afile

    ******created-and-launch-rocket.sh**********

***********************************************************************


************************************************************************

  now to exicute script by using "$bash"

  ***$bash creat-and-launch-rocket.sh***

***********************************************************************



