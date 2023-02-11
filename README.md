# Convert_string_into_a_datetime_object


If you want Convert string date into a datetime. Then Lets do! 

      from datetime import datetime

      date_string = "Feb 2 2023  8:20PM"
      datetime_object = datetime.strptime(date_string, '%b %d %Y %I:%M%p')
      print(datetime_object)
