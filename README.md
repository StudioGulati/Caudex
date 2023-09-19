# Caudex

## Vision and scope

### Problem statement

**Project background** — There is currently no centralized repository of knowledge on game studies and computer games research in particular. One has to search different databases in order to find information relevant to academic endeavors, manually cross-referencing different types of resources such as articles, videos, podcasts, source code, etc., associated with the object of study. It is even more arduous to clearly identify the research context, as the computer game industry involves so many individuals, organizations, and technologies.

**Users**
- **Researchers** must be able to find relevant resources and contextual information about any topic related to computer games. Moreover, they must be able to selectively save query results and associate them with each other. In case the source for a result is not available anymore, they would need to access an archived copy.
- **Practitioners** must be able to access a newsfeed of recent publications about the game industry.
- **Administrators** must be able to manage users and view both product and growth metrics.

**Risks**
- The needs of our potential users: if there is no interest in an authoritative knowledge base, the opportunity will have to be trashed.
- The use of graph structures for semantic queries: if the underlying technology does not support our goal of delivering high quality results in context, we will have to explore other solution ideas.

**Assumptions**
- Researchers and practitioners are having a hard time keeping up to date with news items and publications because of the fragmentation of information sources.
- Researchers are having a hard time looking for resources relevant to their queries because of the lack of academic databases specifically focused on game studies.
- Researchers might be overlooking valuable insights related to their queries because the tools they use do not expose inferred contexts.
- A partially crowd-sourced knowledge base is likely to be adopted by researchers and practitioners alike.
- A graph database will not only improve the quality of the results, but also yield additional information, both explicitly and implicitly derived.

### Vision of the solution

**Vision statement** — The project will serve as an authoritative knowledge base on game studies and computer games research in particular. It will provide researchers with not only resources directly relevant to their object of study, but also extensive contextual information, making it an indispensable academic tool. They will be able to rely on a single software to find everything about their queries.

**List of features**
1. **Web feed** — Users should be able to see a list of recent news items from reputable sources. If known to the system, resources in the list should be annotated with contextual information. Authenticated users should be able to mark these resources as irrelevant or, on the contrary, capture them as entities, and associate them with other entities.
2. **Web search** — Users should be able to use web queries to find resources of interest. Results should be grouped by type or source, and resources already known to the system should be clearly indicated. Authenticated users should be able to mark irrelevant results as such. Users with administrative privileges should be able to add support for new sources and retire deprecated sources.
3. **Knowledge creation** — Authenticated users should be able to capture resources as entities and create relationships between entities, as well as map properties across sources. They should also be able to submit references (URL, DOI, ISBN, etc.) to resources that the system failed to find, and suggest new entity labels and relationship types.
4. **Knowledge curation** — Periodically, the system should create lists of recent search results with corresponding entities/relationships suggestions. Only users with administrative privileges should be able to accept or reject these suggestions.
5. **Knowledge visualization** — When inspecting an entity, users should be able to view and filter other surrounding entities according to entity labels, relationship types, property values, and distance.
6. **Knowledge sharing** — Users should be able to share links to entities via various social media platforms.
7. **Source archive** — The system should automatically archive resources that are marked by users as entities. Authenticated users should be able to request that a resource be archived.
8. **Reference management** — Users should be able to generate a citation for any resource known to the system in any citation style. Authenticated users should be able to create customized citation styles.
9. **User management** — Users should be able to register in order to participate in knowledge creation. Users with administrative privileges should be able to vet all registrations as well as block approved accounts.
10. **Product Metrics** — 
11. **Growth Metrics** — 

**Scope of phased release**
- **Release 1** should include *web feed* and parts of *knowledge creation*.
- **Release 2** should include *web search* and the remaining parts of *knowledge creation*.
- **Release 3** should include *knowledge visualization*.
- **Release 4** should include *source archive* and improvements to the UI/UX.
- **Release 5/version 1.0.0** should include *knowledge curation* and further overall improvements.
- Missing features (*knowledge sharing*, *product and growth metrics*, etc.) will be included in releases after **v1.0.0**.

**Features that will not be developed**
- User activity will never be monitored beyond explicit contributions to the knowledge base, and search history in particular will never be tied to a user account.
- The project is not meant to become yet another social network.

## Discovery map

![Discovery map](/assets/images/Caudex_discovery_map.jpg)
