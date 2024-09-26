+++
title = 'Presentation Master Thesis Julian Thomas'
shorttitle = 'Signature Security Revisited: One Dice to Rule Them All'
date = 2023-11-18T19:42:38+01:00
section = 'News/2023'
number = '4'
image = '/img/graduates/julianThomas.png'
release = 'January 31, 2023'
minirelease = 'Jan 31,2023'
draft = false
+++

Security definitions and frameworks are essential for understanding and evaluating the security of cryptographic applications. However, current approaches for creating security definitions often rely on a bottom-up approach, combining and expanding individually described attack vectors. Thus, attack vectors for specific schemes may not be analysed and described, as is the case for signatures. In addition, no generalised and generic model represents the full security context and thus enables a top-down approach.

We present a new model that fully describes the role of randomness in cryptographic applications, taking into account practical experience and all possible attack vectors at an abstract level. To generalise the model, we consider the algorithms' input and output behaviour. In terms of security risks, we consider classical input-based attacks as well as untrusted randomness, leakage and fault attacks. With the resulting security interface, we can thus analyse adversary models in detail and generalise practical approaches. To instantiate the interface, we use a further developed formalisation for the classic security framework of signatures and extend it with all additional adversary models implied by the model.

The interface framework idea is an abstracted and generalised approach to describe security, which can serve as a reference model for further work according to the top-down principle. This allows new connections to be recognised, results to be generalised, and, under certain circumstances, work to be better categorised and compared. In addition, the idea offers a new approach to analysing attack scenarios and thus improves the understanding of security. It remains to be seen to what extent similar modelling and formalisation can be designed for other cryptographic applications.