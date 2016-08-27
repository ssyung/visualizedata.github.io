## Data Sources

### events.json

An array of JSON objects with data on conferences, Meetups, gatherings, hackathons, talks, and other events related to data visualization. All values are strings. 

##### key/value pairs:

* `name`  name of event
* `type`  type of event
* `focus`  brief description of the focus of the event
* `startDate`  the date the event begins, format: mm/dd/yy
* `endDate`  the date the event ends (is the same as startDate if a one-day event), format: mm/dd/yy
* `location`  event location (city, state or country)
* `url`  URL with event information
* `notes`  notes about the event

### datawork.json

An array of JSON objects with data on jobs, internships, data sources, research opportunities, data competitions, and other opportunities to work, collaborate, and find data for academic projects. Values are strings and booleans.

##### key/value pairs:

* `organizationName`  (string) name of organization
* `url`  (string) URL with information about the organization or opportunity
* `data source`  (boolean) =true if this is an established data set or data source
* `dataResources`  (boolean)=true if this involves resources, software, or other tools for the analysis and visualization of data
* `dataCompetition`  (boolean)=true if this is a data hackathon or competition
* `newSchool`  (boolean)=true if this opportunity is affiliated with The New School
* `position`  (boolean)=true if this is a work opportunity: internship, job, or other position, whether paid or unpaid
* `unpaidPosition`  (boolean)=true if this position is unpaid
* `parttimePosition`  (boolean)=true if this position is a paid, part-time position
* `fulltimePosition`  (boolean)=true if this position is a paid, full-time position
* `grantFellowship`  (boolean)=true if this is a grant or fellowship
* `eligibleAcademic`  (boolean)=true if this may be eligible for academic credit
* `dateAdded`  (string) date object was added, format: mm/dd/yy
* `timeSensitive`  (boolean)=true if this is an urgent or time-sensitive request
* `description`  (string) notes about the opportunity
* `contactName`  (string) name of contact person
* `contactEmail`  (string) email address of contact person
