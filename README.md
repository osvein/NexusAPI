# NexusAPI
C wrapper for the NexusMods API

    nmm.nexusmods.com:80
    GET /%s/Sessions/?Login&username=%s&password=%s HTTP/1.1
    POST /%/Sessions/?Validate HTTP/1.1
    GET /%s/Mods/toggleendorsement/%s?lvote=%s&game_id=%s HTTP/1.1
    GET /%s/Mods/%s/?game_id=%s HTTP/1.1
    POST /%s/Mods/GetUpdates?ModList=%s&game_id=%s HTTP/1.1
    POST /%s/Files/GetUpdates?FileList=%s&game_id=%s HTTP/1.1
    GET /%s/Files/indexfrommod/%s?game_id=%s HTTP/1.1
    GET /%s/Files/%s/?game_id=%s HTTP/1.1
    GET /%s/Files/download/%s/?game_id=%s HTTP/1.1
    GET /%s/Core/Libs/Flamework/Entities/User?GetCredentials&game_id=%s HTTP/1.1
    GET /%s/Mods/Find/?name=%s&type=%s&game_id=%s HTTP/1.1
    POST /%s/profiles/GetUserProfiles/?game_id=%s HTTP/1.1
    POST /%s/profiles/GetProfileData/?game_id=%s&profile_id=%s HTTP/1.1
    POST /%s/profiles/ChangeStatus/?game_id=%s&profile_id=%s&share=%s HTTP/1.1
    POST /%s/profiles/RenameProfile/?game_id=%s&profile_id=%s&name=%s HTTP/1.1
    POST /%s/profiles/RemoveProfile/?game_id=%s&profile_id=%s HTTP/1.1
    POST /%s/profiles/GetMissingFiles/?game_id=%s&profile_id=%s HTTP/1.1
    POST /%s/Mods/GetCategories/?game_id=%s HTTP/1.1
    User-Agent: Nexus Client v0.63.15
    Accept: application/json
    
    www.nexusmods.com:443
    GET /%s/ajax/modimages/?user=%d&id=%d&randomcode=%d&gid=%d HTTP/2.0
    Accept: text/html
