# Icinga Events
This repository includes all upcoming Icinga related [events](https://www.icinga.com/events/). You are invited to complete the events list if you think
something is missing.

Events are split into categories, where the filenames describe the category. Depending on the category a field may be 
required or not.

List of fields:

| Field name        | Purpose                               | Required           |
| ----------------- | ------------------------------------- | ------------------ |
| name              | Name of event                         | Yes                |
| date        | Start of the event, format YYYY-MM-DD | Yes                |
| duration          | Duration of the event in days         | Yes                |
| city              | City of the event location            | Yes                |
| state             | State of the event location           | Yes                |
| partner           | Partner organizing the event          | Yes, for trainings |
| partner_link      | Partner website                       | Yes, for trainings |
| registration_link | Registration website                  | Yes                |


## Categories
A list of examples for each cateogry.

### Trainings

Filenaem: `trainings.yml`

Example:

``` yaml
- name: Icinga 2 Advanced
  type: training
  date: 2018-02-06
  duration: 3
  city: Cityname
  state: Statename
  partner: Partner Inc.
  partner_link: https://www.example.com/
  registration_link: https://www.example.com/en/trainings/icinga_trainings/
```


### Icinga Camps

Filename: `icingacamps.yml`

Example:

``` yaml
- name: Icinga Camp Cityname
  type: camp
  date: 2018-03-08
  duration: 1
  city: Cityname
  state: Statename
  registration_link: https://www.icinga.com/events/icinga-camp-cityname/
```

### Conferences

Filename: `conferences.yml`

Example:

``` yaml
- name: SuperConference
  type: conference
  date: 2018-03-01
  duration: 2
  city: Cityname
  state: Statename
  registration_link: http://example.com/
```

### Meetups

Filename: `meetups.yml`

Example:

``` yaml
- name: Icinga Meetup Cityname
  type: meetup
  date: 2018-03-23
  duration: 1
  city: Cityname
  state: Statename
  registration_link: https://www.meetup.com/Icinga-Cityname-Meetup/events/1234567890/
```

