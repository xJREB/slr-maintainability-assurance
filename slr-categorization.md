# Research Categorization Taxonomy

> We derived a threefold set of category types to structure the identified publications: 3 *architectural* categories, 5 *methodical* categories, and 9 *thematic* categories.


| **Type**      | **Description**                                                                                                                                           | **Mandatory** | **Multiple**             |
| :------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------ | :----------------------- |
| Architectural | Contains three categories that determine if a publication focuses on *SOA*, *microservices*, or *both* styles.                                            | Yes           | No                       |
| Methodical    | Contains five categories that either determine the used research method (e.g. *literature study*) or the study’s contribution (e.g. *model or taxonomy*). | No            | Yes                      |
| Thematic      | Contains nine categories that determine the topic of a publication, i.e. subfields of maintainability assurance.                                          | Yes           | Yes (except for *other*) |

### Methodical Categories

- **Case, Field, or Empirical Study:** the publication either describes a case study (e.g. demonstrating an approach with an example system), a field study (e.g. analyzing an industry system), or an empirical study (e.g. a survey, interviews, or a controlled experiment)
- **Literature Study:** the publication presents the results of a literature study like an SLR or a systematic mapping study
- **Model or Taxonomy:** the publication contributes a (meta) model or taxonomy to further the conceptual understanding of a topic
- **Process or Method:** the publication defines a method or process, i.e. a sequence of activities to achieve a certain goal
- **Reference Architecture or Tool:** the publication either describes a reference architecture (an abstract and reusable template to create system architectures) or a tool to e.g. mitigate manual efforts

### Thematic Categories

- **Architecture Recovery and Documentation:** relying on architecture reconstruction (if no current documentation is available) or on general architecture documentation support to increase analyzability and therefore maintainability
- **Model-Driven Approaches:** approaches that rely on model-driven engineering to reduce long-term maintenance efforts with e.g. code generation from machine-readable models
- **Patterns:** applying patterns specifically designed for service orientation to systematically improve maintainability-related aspects or to describe service evolution
- **Antipatterns and Bad Smells:** conceptualizing service-based antipatterns and bad smells or providing detection approaches for them to identify maintainability weaknesses
- **Service Identification and Decomposition:** approaches to identify suitable service boundaries for functionality or to decompose large existing services into more fine-grained ones that are more beneficial for maintainability
- **Maintainability Metrics and Prediction:** conceptualizing or evaluating service-based metrics to analyze or predict maintainability
- **Change Impact and Scenarios:** approaches for analyzing the potential propagation of service changes or general scenario-based maintainability evaluation
- **Evolution Management:** general approaches to support or improve the overall service evolution process via e.g. systematic planning techniques, accelerating the process, increasing fault tolerance, or mitigating other negative consequences
- **Other:** all papers that could not be assigned to one of the other categories were sorted into this one