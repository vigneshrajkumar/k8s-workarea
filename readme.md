# Container Orchestration Playground

- Start entities in the following order
    1. start redis pod
    2. start postgres pod
    3. start workers deployment
    4. start result app deployment
    5. start voting app deployment


# Questions
1. how do i ensure the order of starting?
2. datastores cannot have multiple instances, what should i do in such cases?