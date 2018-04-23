# clamav-role

This role is designed to be used in tandem with the various other methods for
file scanning/upload scanning in the rest of the infrastructure.

For an overview of how the app-scanning works, and the dedicated infrastructure
scanning, take a look in the appropriate Confluence documentation. DevOps and
Architects should be able to assist. 

## Testing

Test with `$ molecule test`

EICAR is also in place, so that if an infection is NOT found, the build fails.
