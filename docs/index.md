---
SPDX-FileContributor: SPDX AI Working Group and its Contributors
SPDX-FileType: DOCUMENTATION
SPDX-License-Identifier: CC0-1.0
---

# SPDX AI Working Group

Welcome to the **SPDX AI Working Group** website.

This technical working group focuses on developing and maintaining the
[AI][ai-profile] and [Dataset][dataset-profile] profiles of the
[System Package Data Exchange™ (SPDX®) specification][spdx-spec].

Here's a minimal example of an SPDX 3.0 AIPackage shown in
two formats — JSON and RDF/Turtle.
Use the tabs to switch between representations.

=== "JSON"

    ```json
    {
      "@context": "https://spdx.org/rdf/3.0/spdx-context.jsonld",
      "@graph": [
        {
          "type": "ai_AIPackage",
          "spdxId": "https://example.org/model-abc123",
          "name": "sentiment-classifier",
          "creationInfo": {
            "type": "CreationInfo",
            "created": "2025-01-15T10:00:00Z",
            "createdBy": [ "https://example.org/agent/ai-team" ]
          },
          "software_packageVersion": "1.1.2",
          "software_primaryPurpose": "model",
          "software_downloadLocation": "https://github.com/example.org/model-abc/",
          "ai_domain": [
            "sentiment analysis",
            "natural language processing"
          ],
          "ai_energyConsumption": {
            "type": "ai_EnergyConsumption",
            "ai_inferenceEnergyConsumption": [
              {
                "ai_energyQuantity": "0.0000036",
                "ai_energyUnit": "kilowattHour",
                "type": "ai_EnergyConsumptionDescription"
              }
            ]
          },
          "ai_hyperparameter": [
            {
              "type": "DictionaryEntry",
              "key": "epoch",
              "value": "100"
            }
          ],
          "ai_metric": [
            {
              "type": "DictionaryEntry",
              "key": "f1",
              "value": "0.4669192"
            }
          ]
        }
      ]
    }
    ```

=== "Turtle"

    ```turtle
    @prefix spdx: <https://spdx.org/rdf/3.0.1/terms/Core/> .
    @prefix spdx-sw: <https://spdx.org/rdf/3.0.1/terms/Software/> .
    @prefix spdx-ai: <https://spdx.org/rdf/3.0.1/terms/AI/> .
    @prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

    <https://example.org/model-abc123>
        a spdx-ai:AIPackage ;
        spdx:spdxId "https://example.org/model-abc123" ;
        spdx:name "sentiment-classifier" ;
        spdx-sw:packageVersion "1.1.2" ;
        spdx-sw:primaryPurpose "model";
        spdx-sw:downloadLocation <https://github.com/example.org/model-abc/> ;
        spdx-ai:domain "sentiment analysis", "natural language processing" ;
        spdx-ai:energyConsumption [
            a spdx-ai:EnergyConsumption ;
            spdx-ai:inferenceEnergyConsumption [
                a spdx-ai:EnergyConsumptionDescription ;
                spdx-ai:energyQuantity "0.0000036"^^xsd:decimal ;
                spdx-ai:energyUnit "kilowattHour"
            ]
        ] ;
        spdx-ai:hyperparameter [ a spdx:DictionaryEntry ; spdx:key "epoch" ; spdx:value "100" ] ;
        spdx-ai:metric [ a spdx:DictionaryEntry ; spdx:key "f1" ; spdx:value "0.4669192" ] .
    ```

SPDX AI and Dataset profiles can be used to comprehensively document AI systems
and datasets, on top of the existing software component information that
the core SPDX specification provides.

Overview of an AI package, from the AI BOM in [AI Example 02][ai-ex-02]
(click on the diagram to enlarge):

[![AI package overview](./img/ai-example-02-overview.png)](./img/ai-example-02-overview.png)

Details of some information categories that the AI BOM captures:

[![AI package zoom in](./img/ai-example-02-zoomin.png)](./img/ai-example-02-zoomin.png)

See more examples in the [Examples](./examples.md) section.

Want to improve this? See [Contribute](./contribute.md) section.

[ai-profile]: https://spdx.github.io/spdx-spec/latest/model/AI/AI/
[dataset-profile]: https://spdx.github.io/spdx-spec/latest/model/Dataset/Dataset/
[spdx-spec]: https://spdx.org/specifications/
[ai-ex-02]: https://github.com/spdx/spdx-examples/tree/master/ai/example02
