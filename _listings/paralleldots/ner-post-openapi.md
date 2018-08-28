---
swagger: "2.0"
x-collection-name: ParallelDots
x-complete: 0
info:
  title: ParallelDots Name Entity Recognition
  description: |-
    # Introduction
    What does your API do?

    Named-entity recognition(NER) can identify individuals, companies, places, organization, cities and other various type of entities. API can extract this information from any type of text, web page or social media network.

    # Overview
    Things that the developers should know about

    The API accepts the input parameters as form-data.

    Response will be in JSON as shown below:

    ```
    {
        "usage": "By accessing ParallelDots API or using information generated by ParallelDots API, you are agreeing to be bound by the ParallelDots API Terms of Use: http://www.paralleldots.com/terms-and-conditions",
        "entities": [
            {
                "category": "name",
                "name": "Donald Trump",
                "confidence_score": 0.977811
            },
            {
                "category": "place",
                "name": "United States",
                "confidence_score": 0.982107
            }
        ]
    }

    ```

    # Authentication
    What is the preferred way of using the API?

    An API key is required to be sent as a parameter to authenticate your requests.


    # Rate limit
    Is there a limit to the number of requests an user can send?

    There is no rate limit as such but too many concurrent requests will throw 504 time-out error from nginx.
  version: 1.0.0
host: apis.paralleldots.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ner:
    post:
      summary: Name Entity Recognition
      description: |-
        # Introduction
        What does your API do?

        Named-entity recognition(NER) can identify individuals, companies, places, organization, cities and other various type of entities. API can extract this information from any type of text, web page or social media network.

        # Overview
        Things that the developers should know about

        The API accepts the input parameters as form-data.

        Response will be in JSON as shown below:

        ```
        {
            "usage": "By accessing ParallelDots API or using information generated by ParallelDots API, you are agreeing to be bound by the ParallelDots API Terms of Use: http://www.paralleldots.com/terms-and-conditions",
            "entities": [
                {
                    "category": "name",
                    "name": "Donald Trump",
                    "confidence_score": 0.977811
                },
                {
                    "category": "place",
                    "name": "United States",
                    "confidence_score": 0.982107
                }
            ]
        }

        ```

        # Authentication
        What is the preferred way of using the API?

        An API key is required to be sent as a parameter to authenticate your requests.


        # Rate limit
        Is there a limit to the number of requests an user can send?

        There is no rate limit as such but too many concurrent requests will throw 504 time-out error from nginx.
      operationId: NerPost
      x-api-path-slug: ner-post
      parameters:
      - in: formData
        name: api_key
      - in: formData
        name: text
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Name
      - Entity
      - Recognition
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---