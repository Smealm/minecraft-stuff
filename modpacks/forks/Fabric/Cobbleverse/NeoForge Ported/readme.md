cobberverse version 1.5-CF

changes:
1. mod loader changed from fabric to neoforge
2. added fabric compatiblity layer using [Sinytra Connector](https://modrinth.com/mod/connector), [Connector Extras](https://modrinth.com/mod/connector-extras) and [Forgified Fabric API](https://modrinth.com/mod/forgified-fabric-api)

note: this fork has not been tested in any way shape or form.
actions taken: 
1. make fresh cobbleverse install with all optional mods enabled
2. note minecraft version
3. download fresh minecraft instance with same version but with neoforge
4. download fabric compatible layer
5. go through every cobbleverse mod and download neoforge equilivant. if not applicable download fabric version.
6. copy over folders:
6a. config/
6b. datapacks/
6c. resourcepacks/
6d. shaderpacks/
7. package for both curseforge and modrinth