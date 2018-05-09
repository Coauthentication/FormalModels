# Coauthentication Formal Models

Six coauhtentication versions are formally modelled and verified using [ProVerif](http://prosecco.gforge.inria.fr/personal/bblanche/proverif/).

Protocols shown in Coauthentication (in Proceedings of the ACM Symposium on Applied Computing):

- Figure 1: co-auth-full-sym-run-1--3
- Figure 2: co-auth-full-without-challenge-sym-run-1--3
- Figure 3: co-auth-full-without-challenge-forwarding-sym-run-1--3
- Figure 4: co-auth-all-public-without-challenge-forwarding-sym-run-1--3

### Build Setup

To test coauthentication models:

- Download and install [ProVerif](http://prosecco.gforge.inria.fr/personal/bblanche/proverif/)
- Run ProVerif by passing the models as a parameter (e.g., `./proverif co-auth-full-sym-run-1.pv`)

