# Hi, I'm Adam.

I'm an avid pythonista who sometimes finds himself writing Rust, Typescript or Go. I don't work in tech and don't develop professionally, but I aim to write professional code. Let me know if I fall short; not working in the industry, I can sometimes miss the obvious approach. On the plus side, I occasionally stumble into novel approaches too. My work here is just an extension of my obsessive need to solve interesting problems and go way (way) too deep in solving them. For me, all of the fun is in the problem solving process, at least in my personal life.

My interests are diverse and continually changing. They include reinvisioning ideas with an AI/ML-first perspective, data science, cryptography, vanquishing non-native plants and sometimes successfully growing natives, and being a human multitool (from car and HVAC maintenance and construction to photography).

## 🦸 My Superpowers 🦸

- **Blitzkrieg Learning**: Understanding what I don't know and need to know at super speed.
- **Zero fear**: No hesistation...ever.
- **Asking questions no one else imagines**: I just think differently. 
- **Seeking nuance**: I'm suspicious of problems that look simple, because usually an important detail or consequence wasn't considered. Sometimes I'm pleasantly surprised when a solution easily falls into place.
- **Breathing life into ideas**: I'm crazy good at navigating ambiguous problems and chipping away at abstract ideas.
- **Writing for humans**: I'm obsessed with plain, approachable writing.

... with all superpowers there's a cost. You can imagine for yourself how each of those can backfire sometimes.

## I'm currently focused on

🌱 **[ChatHoard](https://github.com/seekinginfiniteloop/ChatHoard** a FOSS webapp that started as a place to store and search my LLM chats (e.g. ChatGPT, Claude), but is rapidly growing into scope into a private, collaborative space to mine, organization, share and collaborate on LLM generated content... because I think I'm not the only one who needs a model agnostic space to make the most of their data. It is built on [FastAPI](https://github.com/tiangolo/fastapi)/[Pydantic](https://github.com/pydantic/pydantic), [React](https://github.com/facebook/react)/[ChakraUI](https://github.com/chakra-ui/chakra-ui), and uses [Qdrant](https://qdrant.tech/)/[DocArray](https://github.com/docarray/docarray) for intelligent vector search. It's designed to be both locally deployable and also massively scalable.

## My Backburner

I have a few projects I intend to get to a stable place eventually... 

- **[AutoKeyring](https://github.com/seekinginfiniteloop/AutoKeyring)** A tool solving the problem of passwordless Linux logins; it securely handles unlocking Gnome/KDE keyrings and wallets ([Freedesktop.org SecretService](https://specifications.freedesktop.org/secret-service/latest/) is the underlying cryptographic management service. It's dated... maybe some day I'll write a replacement) when you login using [TPM 2.0](https://support.microsoft.com/en-us/topic/what-is-tpm-705f241d-025d-4470-80c5-4feeb24fa1ee) or [Yubikey](https://www.yubico.com/products/) as a root key generator (SecretService only accepts passwords for keyrings/wallets, so AutoKeyring derives a secure hash to use as a password or derives a secret to encrypt and store a password for unlocking operations.
- **[Amazon_Job_Alertbot](https://github.com/seekinginfiniteloop/Amazon_Job_Alertbot)** *Mostly* a tongue-in-cheeck project to gain a deep practical understanding of AWS serverless app dev/deployment. It's a self-deploying AWS serverless system of microservices that simply checks amazon.jobs and provides better search settings and an alerts agent. I started it from irony because [amazon.jobs](amazon.jobs) doesn't offer a job alerts service. It works, I just need to finish the search UI. Maybe one day someone at Amazon will happen upon it and use some of it to implement an actual alerts service (they would only need a small portion because they have amazon.jobs already)...
- **[fedcal](https://github.com/seekinginfiniteloop/fedcal)** A [pandas](https://github.com/pandas-dev/pandas) namespace extension that adds Federal timeseries information to native pandas objects. The offsets module is done and serves offsets for factors that affect federal productivity, and actually adds vectorized operations where there weren't vectorized operations in pandas Offsets (another backburner is proposing those changes to pandas itself). There is also an accompanying database of funding/appropriations status for all top-level federal departments since 1975 (i.e. shutdowns, continuing resolutions, etc). The library aims to enable sophisticated statistical studies of the effects of federal budget and productivity processes on both government function and the unimagined consequences (i.e. impacts on local businesses, etc). I'm still thinking through how best to deliver the budget data for clean integration with pandas.  Another path is taking it back a step, using python (or numpy) objects and creating an interface so it can integrate with not just pandas but polars and other dataframe libraries.

