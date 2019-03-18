# Coauthentication Formal Models

Several coauhtentication versions are formally modelled and verified using [ProVerif](http://prosecco.gforge.inria.fr/personal/bblanche/proverif/).

Protocols shown in Coauthentication:

- Figure 1: co-auth-full-sym-run-1--3
- Figure 2: co-auth-full-without-challenge-sym-run-1--3
- Figure 3: co-auth-full-without-challenge-forwarding-sym-run-1--3
- Figure 4: co-auth-all-public-full-sym-run-1--3
- Figure 5: co-auth-all-public-without-challenge-sym-run-1--3
- Figure 6: co-auth-all-public-without-challenge-forwarding-sym-run-1--3
- Figure 7: co-auth-all-public-full-asym-run-1--3
- Figure 8: m-out-of-n/co-auth-full-3-out-of-n-sym-run-1--3
- 3-out-of-n: m-out-of-n/co-auth-full-3-out-of-n-sym-run-1--3
- Figure 1 (stateful): stateful/co-auth-full-sym-run-1--3
- Figure 2 (stateful): stateful/co-auth-full-without-challenge-sym-run-1--3
- Figure 3 (stateful): stateful/co-auth-full-without-challenge-forwarding-sym-run-1--3

### Build Setup

To test coauthentication models:

- Download and install [ProVerif](http://prosecco.gforge.inria.fr/personal/bblanche/proverif/)
- Download and install [StatVerif](https://markryan.eu/research/statverif/)
- Run ProVerif by passing the models as a parameter (e.g., `./proverif co-auth-full-sym-run-1.pv`)
- Run StateVerif by passing the stateful models as a parameter (e.g., `./statverif stateful/co-auth-full-sym-run-1.pv`)