# IoT-based self-operating distributed energy supply system for lighting template

Co-author: Bram van Berlo (b.r.d.v.berlo@tue.nl)
Contribution: assignment conception, UML architecture and viewpoint definition, feedback on computer process format

### Situation

In recent years the price of electric energy increased drastically in parallel with the rise of the fossil fuel prices. Smart grids are electricity networks that cost-efficiently integrate electric energy stakeholder actions to supply energy with lower energy loss than traditional electricity networks. Smart grids can be used to supply energy to both private (e.g. homes, offices) and public lighting infrastructure, with lower prices. Energy production/consumption efficiency can be increased if neighboring infrastructures (homes, office buildings, etc.) can exchange excess energy with each other at shorter distances. Therefore, small IoT marketplace auction based distributed energy supply systems (still managed by large energy producers) are expected to launch in the near future. [When the production of neighboring stakeholders is not enough, it is still possible to fall back to drawing/buying energy directly from large producers in the traditional way.]

### Task / Action

Students implement an IoT-based distributed energy supply system (simulated) for lighting in a smart building. The main large energy provider may ask the smart building to reduce its energy demand. However, this time, prior to dimming the lights to stay under the determined energy consumption limit, the smart building first tries to acquire energy from alternative sources (the IoT energy marketplace), through the energy supply facilitation system.

### Learning outcomes

- Build an IoT-based digital self-operating lighting energy supply system with the help of detailed scenarios that describe required (client-server) behavior. Given are: a client-server programming framework, an energy auctioning marketplace interface.
- Take care of interoperability as a non-functional requirement, while also making sure the communication and management protocols used are in accordance with the resource limitations of constrained devices.
