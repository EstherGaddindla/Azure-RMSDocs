# class mip::FileEngine::Settings 
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public inline Settings(const std::string& id, const std::string& clientData, const std::string& locale)  |  Creates an instance with the given parameters.
public inline Settings(const Identity& identity, const std::string& clientData, const std::string& locale)  |  Creates an instance with the given parameters.
public inline const std::string& GetId() const  |  Returns the engine Id.
public inline const Identity& GetIdentity() const  |  Returns the engine Identity.
public inline void SetIdentity(const Identity& identity)  |  Sets the engine identity.
public inline const std::string& GetClientData() const  |  Returns the engine client data.
public inline const std::string& GetLocale() const  |  Return the engine locale.
public inline void SetCustomSettings(const std::vector<std::pair<std::string, std::string>>& value)  |  Sets a list of name/value pairs used for testing and experimentation.
public inline const std::vector<std::pair<std::string, std::string>>& GetCustomSettings() const  |  Gets a list of name/value pairs used for testing and experimentation.
public inline void SetSessionId(const std::string& sessionId)  |  Sets the engine session id.
public inline const std::string& GetSessionId() const  |  Return the engine session id.
  
## Members
  
### Settings
Creates an instance with the given parameters.
Use this to create [Settings](#classmip_1_1_file_engine_1_1_settings) to call LoadEngineAsync to load an existing engine (previously added via AddEngineAsync).
  
#### Parameters
* id Set it to the unique engine id generated by AddEngineAsync.
  
### Settings
Creates an instance with the given parameters.
Use this to create [Settings](#classmip_1_1_file_engine_1_1_settings) to call AddEngineAsync to add a new engine.
  
#### Parameters
* identity Identity info of the user for whom the engine needs to be added.
  
### GetId
Returns the engine Id.
  
### GetIdentity
Returns the engine Identity.
  
### SetIdentity
Sets the engine identity.
  
### GetClientData
Returns the engine client data.
  
### GetLocale
Return the engine locale.
  
### SetCustomSettings
Sets a list of name/value pairs used for testing and experimentation.
  
### GetCustomSettings
Gets a list of name/value pairs used for testing and experimentation.
  
### SetSessionId
Sets the engine session id.
  
### GetSessionId
Return the engine session id.