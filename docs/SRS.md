## Requirement Diagram

```mermaid
requirementDiagram
    requirement FRQ_1_1 {
    id: 1
    text: Registration client
    risk: high
    verifymethod: test
    }

    requirement FRQ_1_2 {
    id: 2
    text: Authentication client
    risk: high
    verifymethod: test
    }

    requirement FRQ_1_3 {
    id: 4
    text: Add restoran
    risk: high
    verifymethod: test
    }

    requirement FRQ_1_4 {
    id: 3
    text: Cancel Registration
    risk: high
    verifymethod: test
    }

    requirement FRQ_1_5 {
    id: 5
    text: Add 1XBET
    risk: low
    verifymethod: test
    }

    requirement FRQ_1_6 {
    id: 7
    text: Add 1XBET
    risk: low
    verifymethod: test
    }

    requirement NFR_1_1 {
    id: 52
    text: Performance
    risk: high
    verifymethod: test
    }

    requirement NFR_1_2 {
    id: 6
    text: 10,000 USERS
    risk: high
    verifymethod: test
    }

    requirement NFR_1_3 {
    id: 8
    text: system response 3ms
    risk: high
    verifymethod: test
    }

    requirement NFR_1_4 {
    id: 78
    text: database sql
    risk: high
    verifymethod: test
    }


    requirement NFR_1_53 {
    id: 10
    text: 1000 sessions at a moment
    risk: high
    verifymethod: test
    }

    element BRQ_1_1 {
    type: BRQ

    }

    BRQ_1_1 - satisfies -> FRQ_1_1
    FRQ_1_4 - contains -> FRQ_1_1
    BRQ_1_1 - satisfies -> FRQ_1_2
    BRQ_1_1 - satisfies -> FRQ_1_5
    FRQ_1_2 - contains -> FRQ_1_3
    BRQ_1_1 - satisfies -> NFR_1_1
    NFR_1_1 - contains -> NFR_1_2
    NFR_1_1 - contains -> NFR_1_3
    NFR_1_1 - contains -> NFR_1_4
    BRQ_1_1 - satisfies -> FRQ_1_6


```

