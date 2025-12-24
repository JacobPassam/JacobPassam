## Hi there!

I'm a 2nd-year MChem Chemistry student at Durham University with interests at the chemistry-biology interface. My research interests lie in applying computational methods to chemical simulations, and I have a background in distributed systems engineering and large-scale project work as evidenced below.

This site mainly hosts some of my earlier project work (c. 2020-2022) in Java and Python.

### Highlights

| Project | Stack | Features |
| :-- | :-- | :-- |
| [Core](https://github.com/MaritimeMC/core) <br/></br>An exhaustive kernel for the below projects. | Java 17, Gradle, Redis, SQL | <ul><li>`ThreadPool` execution environment used to offload heavy I/O tasks from the main 'tick' loop</li><li>Role-based access control implemented</li><li>TOTP 2FA algorithm implemented with Google Authenticator.</li> </ul>|
| [Masthead](https://github.com/MaritimeMC/Masthead) <br/><br/>An in-house dynamic infrastructure management system, monitoring server health and capacity. | Java, Redis, Docker, External APIs | <ul><li>Engineering of a Kubernetes-esque system to spin-up/kill server containers based on demand.</li><li>Implementation of a self-healing system using Redis to automatically register & de-register servers.</li></ul> |
| [Proxy & Load Balancer](https://github.com/MaritimeMC/Proxy-Plugin) <br/><br/>Reverse proxy and traffic controller.| Java | <ul><li>Load-balancer with multiple heuristic strategies to optimise server density</li><li>Utilised Redis pub/sub to syncronise demand data in real-time.</li></ul>  |
| [Block Party Web](https://github.com/MaritimeMC/block-party-web) <br/><br/>Real-time full-stack visualisation dashboard allowing live metric rendering.| TypeScript, React, Node.js, Socket.io | <ul><li>Client-server state syncronisation.</li></ul> |

More recent technical experience includes Python for lab-based data analysis and visualisation. 

I'm currently looking into quantum chemistry simulations and practising the use of machine learning in biochemistry, and I am keen to bridge the gap between chemistry and high-performance software architecture.

He/him. Contactable at jacob.j.passam@durham.ac.uk.
