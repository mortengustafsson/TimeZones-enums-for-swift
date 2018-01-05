# TimeZones-enums-for-swift
Swift: Enum for Time Zone names.

Add this file into you project when working with Time Zones. Instead of writing ex. "Europe/London" you can just write TimeZones.Europe.London.

Using TimeZones will help you prevent typos, and names are easily and quickly found with help from Xcode's Auto-completion. 

Examples:  

London:

    let londonTimeZone = NSTimeZone(name: TimeZones.Europe.London.rawValue)


Sydney:

    let sydneyTimeZone = NSTimeZone(name: TimeZones.Australia.Sydney.rawValue)
    

Copenhagen:
    
    let copenhagenTimeZone = NSTimeZone(name: TimeZones.Europe.Copenhagen.rawValue)

Middelfart: 

    let middelfartTimeZone = NSTimeZone(name: TimeZones.Europe.Copenhagen.rawValue)
    // Middelfart is a small town, with a funny name, in Denmark. 
    // Middelfart is located in the same time zone as Copenhagen and therefore use .Copenhagen as time zone name. 
    
    
GMT:

    let GMTTimeZone = NSTimeZone(name: TimeZones.GMT.rawValue)
    

TimeZones is based on names from the list on wikipedia:
https://en.wikipedia.org/wiki/List_of_tz_database_time_zones
