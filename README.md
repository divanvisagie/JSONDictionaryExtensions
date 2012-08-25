JSONDictionaryExtensions
========================

This is an NSDicionary extension for easy conversion to and from JSON in the NSData format

To use simply #import "JSONDictionaryExtensions.h" in the class you and to use it.It will add the following 
functionality to NSDictionary objects

[NSDictionary dictionaryWithJSONData:data] 

 - Creates a dictionary object from JSON data

 dictionary.JSONValue

 - Returns JSON data representation of NSDictionary

 dictionary.JSONString

 - Returns a JSON string representation of NSDictionary