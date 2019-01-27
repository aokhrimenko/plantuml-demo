# External links
Demo repository: https://github.com/aokhrimenko/plantuml-demo

PlantUML home page: http://plantuml.com/

# Use cases
## Document upload
As user I want to be able to upload documents via Web form. Document parse result should be available via email notification.
System should update artifacts storage in case of success. Document processing should run asynchronously therefore user won't wait for profeccing result.

## Technical details

Actors:
- user
- upload form
- document processor
- notification system
- queue
