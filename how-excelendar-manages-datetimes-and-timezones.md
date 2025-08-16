# How Excelendar manages datetimes and timezones

Excelendar has a very robust system in place for managing datetimes and timezones. When importing a calendar in a sheet, there are five essential columns that are displayed: Display Start Date, Display Start Time, Display End Date, Display End Time, Event Start Date, Event Start Time, Event End Date, Event End Time, Event Start Timezone and Event End Timezone. While this may seem confusing at first, this system allows for maximum flexibility when it comes to managing datetimes and timezones.&#x20;

The Display datetime columns correspond to the dates and times of a particular event, in the sheet display timezone configured in the add-in settings. This is set to your Outlook mailbox timezone by default. The Event datetime columns, however, correspond to the dates and times in the event's own timezone, specified by the Event Start Timezone and Event End Timezone column. In Outlook Calendar, events can have their own timezone, and different timezones for the start datetime and end datetime, which is notably useful for international travel.

When an edit is made in a Display datetime column, a corresponding edit is automatically made to the corresponding Event datetime column, transposed to the corresponding timezone of the event. You can hide the Event datetime columns if you are only editing Display datetime columns.
