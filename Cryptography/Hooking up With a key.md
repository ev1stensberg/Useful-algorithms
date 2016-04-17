#Hooking up our functions with keys 

k = key
K = a given set of possible keys

k  ∈ K

- E: M x K -> C 
- D: C x K -> M

#Correctness property: 

∀ m(1)k : D(k)(E(k)(m)) = m 

#Usage

Makes our functions rely on two public keys shared betwen two parties, the encryption and the decryption.
