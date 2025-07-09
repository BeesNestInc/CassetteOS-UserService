## v0.4.8-cs1.0.0
### Changes

- Based on CasaOS-UserService v0.4.8 (`452aeac7f1a57fa936d11f9460e286bea3c34db7`)
- Replaced module paths to use our own GitHub fork instead of the original IceWhaleTech repository  
  (e.g., `github.com/IceWhaleTech/CasaOS-UserService` → `github.com/BeesNestInc/CassetteOS-UserService`)
- Adjusted GitHub Actions and goreleaser settings for CassetteOS environment
- Removed IceWhale-specific OpenAPI sync workflows

### Note

Although we initially intended to customize from the upstream `v0.4.8` tag directly, the code at that tag was in the middle of a migration from Echo to Gin and failed to build.  
We therefore started from the `main` branch at the time of forking, which was already Gin-based and buildable.
