

## Development of an in-vehicle middleware

In the context of in-vehicle embedded systems, a middleware layer is intended to mask the heterogeneity of platforms and to provide high level communication services to applicative tasks. In addition, it is a software architecture shared between car makers and third-part suppliers, ensuring the portability and interoperability of the applicative level components. In this context, the interoperability covers the interfaces between components, and also, the guarantee that at run-time, tasks implementing these components and their data exchanges respect all the required timing constraints (i.e. timing interoperability). This study presents a method aiming at developing the middleware's architecture, and obtaining feasible scheduling parameters for network frames (specifically for CAN frames) and middleware and applicative tasks. The architecture is built from a set of design patterns and is represented by a class diagram that specifies the software components implementing the middleware services. Then, from the events that are handled by the middleware, tasks providing the communication services are precisely identified and a possible implementation targeted at OSEK/VDX OS is discussed. Finally, the scheduling parameters of frames and tasks are determined in such a way that timing constraints on tasks and signals are ensured to be met.

## ZF builds ‘middleware’ to address vehicle software escalation

The Tier 1 auto supplier sees middleware as a vital component if vehicles are to make the most of high-level computing.

Acknowledging the emergence of the “software-defined” vehicle, Tier 1 auto supplier ZF announced that it is in the process of developing a “middleware” platform designed to facilitate communication between a typical new vehicle’s ballooning number of software-controlled components and systems. Company engineers and executives said the first vehicles leveraging the new middleware will be on the road in 2024, but the platform is being created because the industry has to grasp “what the car will look like in the 2030s,” said Dirk Walliser, senior vice president – corporate R&D, Innovation & Technology for ZF Friedrichshafen AG.

“And by the way, it’s being utilized not only for passenger cars, but mostly already in commercial vehicles,” Walliser said. “There we have special operating situations. We have hub-to-hub operation, for example, we have geo-fenced areas, smart plants [and] harbors, for example, where these new functions are already needed. And without that middleware, we couldn’t handle the complexity.” Walliser added that two customers – one in commercial vehicle, one in passenger car – are already participating in projects.

Coinciding with the undertaking to create its middleware platform, ZF also announced it is establishing a Global Software Center to, according to a release, prepare for “new challenges in the triad of software, functions and smart systems” and to proactively pursue “numerous development processes.” Opening in 2021, the Global Software Center will be headed by Nico Hartmann, vice president, Software Solutions & Global Software Center.

“Middleware is the mediator,” said Hartmann, between key vehicle systems and functions that often are created by a list of disparate suppliers and typically are controlled by software discrete from most other aspects of vehicle operations. The company cited as one need for middleware: contemporary vehicles can have as many as 100 electronic control units (ECUs) and each typically has its own software. Meanwhile, electrical/electronic (E/E) architecture development trends are moving toward a centralization strategy in which the system consists of just a few domain control units (DCUs). According to ZF, these kinds of systems will work better with middleware designed to collate their communications and integrate system functions.

“The concept of middleware is not new,” said Hartmann. But for increasingly software-dependent vehicles, he explained, having middleware will better deal with today’s and future E/E architectures and help to “future-proof” them for years to come. “We have to start this transformation right now,” added Walliser.

Benefits in time and effort
The company’s executives said ZF’s new middleware — with its “open” hardware and software protocols — can accelerate and enhance development processes between ZF, automakers and other suppliers. One prime benefit is the potential for perpetually updateable software and even hardware functions that will bring “an end to static lifecycles” for vehicles and their functions, said Walliser. The company also said that the presence of middleware will reduce software development times and allow all parties in the supply chain to concentrate on their software or hardware’s specific functional goals.

The ZF executives speaking with the media declined to speculate about development-time reduction, but did say they believe an optimized middleware environment can allow one software developer to handle the work of what previously might require up to eight individuals. And although that metric seems to imply an intrinsic potential for cost reduction, Walliser emphatically stated, “Middleware is not a cost-cutter — it’s an enabler.”

Hartmann said that although ZF’s middleware is designed to be an “open” architecture, it’s not open in the traditional sense of being publicly accessible: partners will have to form a relationship with ZF before gaining insight about the middleware platform’s details and structure. And “we won’t build every piece of middleware ourselves,” Walliser added.

Another intriguing claim for middleware is its potential as a cybersecurity component; ZF said it can provide “state-of-the-art shielding of the vehicle software environment from external threats or manipulation.” Meanwhile, its hardware and interface “abstractions” help a vehicle to become agnostic to the multiplicity of software and communications interfaces from individual suppliers and developers. In a separate interview with SAE International, Hartmann said a vital aspect of middleware includes its ability to be the intermediary with a vehicle’s overarching software operating system, or OS — a relatively recent innovation for automakers and commercial-vehicle OEMs. Companies such as Volkswagen and Daimler have developed distinct OSs, Hartmann said, and the trend is expected to gain momentum with others in the industry.

Hartmann also noted that some automakers’ and large suppliers’ thinking about software development began to “converge” around the middleware strategy. “We saw that OEMs are at the same level of thinking,” he said, adding that the concept of middleware also seems to align with hardware developers’ efforts to consolidate and reduce the number of vehicle ECUs. “There is a convergence in the market on this concept [of systems integration],” he said.

There is potential that every entity in the supply chain may not see the value of the middleware solution. Some software developers, for example, may interpret automotive-system middleware as merely another application programming interface (API)-type of platform with which to deal.

“We are not alone here — and we will not create the standard for the whole world,” Hartmann said. But he said ZF viewed the development of a middleware platform as “a necessity for ourselves so that we can go down the path of high-level [vehicle] computing.”