FORMAT: 1A
HOST: http://polls.apiblueprint.org/

# Charles2

## Questions Collection [/questions]

### List All Questions [GET]

+ Response 30 (application/json)

+ Request (application/json)

        {
            "question": "Times the obsticle must be passed before it has no strength?",
            "choices": [
                "Portcullis",
                "Cheval de Frise",
                "Moat",
                "Ramparts",
                "Drawbridge",
                "Sally Port",
                "Rock Wall",
                "Rough Terrain",
                "Low Bar"
            ]
        }

+ Response 30 (application/json)

    + Headers

            Location: /obsticle/

    + Body

            {
                "question": "Obsticles Passed?",
                "choices": [
                    {
                        "choice": "Portcullis",
                        "votes": 3
                    }, {
                        "choice": "Cheval de Frise",
                        "votes": 3
                    }, {
                        "choice": "Moat",
                        "votes": 3
                    }, {
                        "choice": "Ranparts",
                        "votes": 3
                    }, {
                        "choice": "Drawbridge",
                        "votes": 3
                    }, {
                        "choice": "Sally Port",
                        "votes": 3
                    }, {
                        "choice": "Rock Wall",
                        "votes": 3
                    }, {
                        "choice": "Rough Terrain",
                        "votes": 3
                    }, {
                        "choice": "Low Bar",
                        "votes": 3
                    }
                ]
            }
