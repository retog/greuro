# GREURO
## A cheaper and more ecological alternative to Bitcoins (and much sexier than GREXIT)

An essential security feature of Bitcoins if the proof of work. Computers solve 
cryptological puzzles as a proof of work when approving changes into the 
blockchain. This proof of work is an elegant solution to allow for a 
decentralized network in an anonymous network. However it brings huge energy 
costs, the *bitcoint network already uses around as much electricity as the 
republic of Ireland*, even though today only a very small fraction of the monetary 
transactions are bitcoins transactions.

A solution: the GREURO is designed to use a trusted central block chain run by 
the Greek State. GREUROs are transferable digital certificates than can be 
converted to EUROs. (Some limitations on how many EUROs can be converted by 
person and day might be in place).

## How does it work?

Compared with the Bitcon block Chains things are quite easy.

### Generations of new GREUROs

The GREUROs are released by the Greek State, basically its a document digitally signed by the Greek State:

    The Hellenic Republic promises to pay the holder of this GREURO the amount of 1 EURO. 
    As holder of this GREURO shall either be the person that can identify as the original 
    holder of this GREURO or any person that can provide cryptographic proof that the 
    orginal holder transferred the rights on this GREURO to them either directly or via 
    a cryptographically proven transfer chain. The first person presenting as holder 
    of this GREURO shall be considered the legitimate owner, to any person subsequently 
    attempting to cash the same GREURO shall be provide cryptograph evidence that
    a person in the transfer chain duplicated the GREURO will be dis.

    Fineprint: max. transaction fee, possibility of temporary limitations, ....

    Number: 43295873

    Intial Owner {
       Name (optional): Alice.
       Public Key: 7F87 5B8C ........
    }

### Forwarding GREUROS

Now Alice who got the first GREURO wants to use it to pay for a drink and consequently 
transfer it to Bob. She basically just takes the above document including its signature 
by the Greek State and add the new owner before signing it with her key (i.e. with the
 secret key that matches the public key in the owner section of the original document.

    [Signed original document]

    I hereby transfer all my rights on this GREURO to the new owner below. I promise 
    that I only transfer this GREURO to the new owner specified it this document and 
    will not cash the GREURO myself.

    New Owner {
       Name (optional): Bob.
       Public Key: 3D63 Fe45 ........
    }

Bob can now either trust Alice and keep the document as it is, or convert it to to 
a new GREURO using the online services of the Greek State. Even though the transaction 
fee to create a brand new GREURO from a transferred one Bob decide not to convert 
the GREURO. Instead he uses the GREURO to pay one his staff member Carol. The 
new digitally singed document is quite similar to the above one


    [The document Alice Signed]

    I hereby transfer all my rights on this GREURO to the new owner below. I promise 
    that I only transfer this GREURO to the new owner specified it this document and 
    will not cash the GREURO myself. If any of the earlier parties in the transfer 
    chain have double spent this GREURO I shall reimburs the new owner in full.

    New Owner {
       Name (optional): Carol.
       Public Key: 8D33 567F ........
    }

Carol can either just trust Bob or convert the GREURO for a brand new one with 
the online service of the Greek State. If nobody double spent Carol will get the 
bran new GREURO (like the one Alice had, except with her name on it). If however 
Alice broke her promise and double spent the GREURO to Dave who cashed (or 
converted) it right away, the Greek Server will refuse to accept Carol's GREURO 
and tell her that Alice double spent the GREURO. Carol will now go back to Bob 
and ask for another GREURO, after refunding Carol Bob will try to find Alice and 
blame himself for having trusted her.

## Advantages compared with Bitcoins

 * Much more energy efficient, thus cheaper transactions
 * Backed by an external value (EUROs) thus more stable

## Advantages for Greece

 * A lot of microcredits from the masses, this would be 4x10^9 € when reaching the volume of Bitcoins.

## Advantages for the rest of us

 * Cheaper payments
 * Infrastructure that could be used with other virtual currencies, allowing for social and personal currencies.
 * Less currency risks than with bitcoins, as we all know how hard the Greek work to pay debts back (while we have no guarantee for the value of the bitcoins).
 * With bitcoins we never know for sure that a transaction won't be reversed, its only a question of computational power invested. By contrast by converting a GREURO we have the guarantee that the transaction cannot be reversed.

## references

 * Energy usage of the Bitcoin network: "the entire Bitcoin mining network is on 
par with Ireland for electricity consumption" 
[http://karlodwyer.github.io/publications/pdf/bitcoin_KJOD_2014.pdf]](http://karlodwyer.github.io/publications/pdf/bitcoin_KJOD_2014.pdf)
