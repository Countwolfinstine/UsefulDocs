Date time in mongo

time_now = datetime.datetime.now()
last_four_hour_date_time = datetime.now() - timedelta(hours = 4)
When datetime object is inserted in mongo, it is automatically converted to ISOdate formate
