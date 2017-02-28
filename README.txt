************************************************************************************************************************
************************************************************************************************************************
This is a sandbox module to pull in Eventbrite events into your Drupal Site. This can be used as a starting point as all
it really does is pull in basic event data from the API, assuming you have a valid API key.

1. Reference the hd_eventbrite_event_pull() function in the .module file to see what content type you must create and
   what fields you need in that content type.
2. Navigate to admin/config/system/eventbrite and put in your API key
3. This is meant to run on cron.
4. There is a field to put a relative path for a 'test' page. The eventbrite_content() function in .module is what is
   used to test what data is coming from the API.