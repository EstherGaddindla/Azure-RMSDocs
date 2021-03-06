# class mip::CustomAction 
[CustomAction](#classmip_1_1_custom_action) is a generic action class that captures all the sub-properties of the action as a property bag. The caller is responsible to understand the meaning of the action.
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public const std::vector<std::pair<std::string, std::string>>& GetProperties() const  |  Get the properties key value pair list.
public ActionType GetType() const  |  Get the type of [Action](#classmip_1_1_action).
  
## Members
  
### GetProperties
Get the properties key value pair list.
  
#### Returns
a key value pair list.
  
### ActionType
Get the type of [Action](#classmip_1_1_action).
  
#### Returns
ActionType The type of derived action this base class can be cast to.