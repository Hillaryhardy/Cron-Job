# Cron-Job

Simple python script implimenting tasks on schedule.

#yaml file




kubectl create cronjob simpletask --image=simpletask.py --schedule="*/5 * * *" --dry-run=client -o yaml task.yaml
