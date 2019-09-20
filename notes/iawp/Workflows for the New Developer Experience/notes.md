# Workflows for the New Developer Experience

- minimizing friction from idea to code to delivering observable business value
- designing the developer workflow

## The Disconnected Modern Developer Experience

- Developers are involved with the entire lifecycle of the product
- different kind of teams require different kind of workflows e.g. e-commerce vs nuclear reactors
- the benefits and drawbacks of breaking systems apart via microservices
- *"decide the workflow you want first and then choose your tools"*
- *developer-centric cloud-based world of work*
- new normal
  1. end-to-end delivery
  2. code changes have to be deployed immediately
  3. developers need to understand business
  4. the closer production, the better. Kubernetes has enabled closing the gap between dev and prod
  5. inner dev has to use real environment. be cautious with shared data
  6. every developer is able to run full software dev cycle
  7. staging delivers low ROI. Instead, favor contract tests and observability in production
- **internal vs external developer experience??**
- companies seem to have a tendency to build their own platform with kubernetes, even if they will not need it
- the business is not around building platforms, but instead about building products

## Building Boundaries around Developer Workflow

- independence ≅ developer experience
- Netflix as a developer community has some guidelines, frameworks, and expectations on how developers build th<eir platforms. They can choose to not follow them, but then they have to be ready to be on call

## Developer and Test Services, Locally, Within a Cluster, or Both?

- engineers want to write code locally
- to enable this engineers can be given their own private kubernetes cluster
- *"a lot of our journey as software engineers is psychology"*
- fast feedback in DevOps and lean environments
  - canary testing by rolling out service to small fraction of traffic
  - shadow traffic - real live traffic into a test service, but not returning data
- testing in production is again something for startups, but not for banking apps
- *"Developer experience isn’t about following certain rules, but rather deciding what suits your specific developer audience"*
- a table that shows what different kinds of pathways different updates require
- always asking: "Where's the boring stuff and pain points to automate?" 

## Conclusion

- *"you should be looking for anyplace to enhance the developers' user experience"*
- make it easy for developers to do the right thing
- *"If you are going to create your own platform, think about developer experience and the workflow before you create the platform"*

## Personal thoughts about the paper

- what are the customer in this context?
- is the customer the developer itself