Set permission to  execute for the shell script

chmod +x script.sh

Modify the crontab file : 


crontab -e

list the content of the crontab

crontab -l

*Cron to run every 5 or 3 min every day


*/5 * * * * /home/luc/test.sh >> /tmp/log.txt 2>&1

or the easy way:

*/3 * * * * /home/luc/test.sh >> /tmp/log.txt 


More info :

https://support.asperasoft.com/hc/en-us/articles/216127358-How-to-run-a-cron-job-every-5-minutes

https://www.thegeekstuff.com/2011/12/crontab-command/

