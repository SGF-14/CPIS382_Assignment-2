# CPIS382_Assignment-2

# XML RDFS files with data for CPIS 382 Assignment 2

This XML RDFS file includes definitions for the following:

### Classes and Subclasses:
- HighSchool
- Person
- - Teacher (subclass of Person)
- - Student (subclass of Person)
- - Manager (subclass of Person)
- - Staff (subclass of Person)
- Room
- - Canteen (subclass of Room)
- - Library (subclass of Room)
- - PrayerPlace (subclass of Room)
- - Stadium (subclass of Room)
- - Pool (subclass of Room)
- - Medical (subclass of Room)
- Course
- Group
- Address
- PhoneNumber
- Email
- Website
- Activity
- ContactInfo

### Properties:
- hasFirstName
- hasLastName
- hasAge
- hasID
- teaches
- memberOf
- hasAddress
- hasPhoneNumber
- hasEmail
- hasWebsite
- hasEstablishYear
- hasZipCode
- hasCourseName
- hasTeacherLeader
- hasFullName
- hasContactInfo
- hasActivityDetails
- hasActivityName

### Sub-properties:
- hasFullName (sub-property of hasFirstName and hasLastName)
- hasContactInfo (sub-property of hasAddress, hasPhoneNumber, hasEmail, and hasWebsite)
- hasActivityName (sub-property of hasActivityDetails)
