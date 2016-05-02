# TimeZones-enums-for-swift
Swift: Enums for Time Zone names.

Add this enum into you project when working with Time Zone names. Instead of writing ex. "Europe/London" you can just write TimeZone.London or just .London.
This Enum will help prevent typos, and uses Xcode's Auto-completion. 

Examples:  

London:

    let londonTimeZone = NSTimeZone(name: .London.rawValue) 


Sydney:

    let sydneyTimeZone = NSTimeZone(name: .Sydney.rawValue) 
    

Copenhagen:
    
    let copenhagenTimeZone = NSTimeZone(name: .Copenhagen.rawValue) 

Middelfart: 

    let middelfartTimeZone = NSTimeZone(name: .Copenhagen.rawValue) 
    // Middelfart is a small town, with a funny name, in Denmark. 
    // Middelfart is located in the same time zone as Copenhagen and therefore use .Copenhagen as time zone name. 
    
    
GMT:

    let GMTTimeZone = NSTimeZone(name: .GMT.rawValue) 
    

TimeZones is based on names from the list on wikipedia:
https://en.wikipedia.org/wiki/List_of_tz_database_time_zones 
