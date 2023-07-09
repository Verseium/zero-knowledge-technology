Day 1: Introduction 

![Day1](https://github.com/Verseium/zero-knowledge-technology/blob/main/images/ZK-Technology.png)

As the story begins, the Guardians of Lumos find themselves gathering in their ancient citadel, their noble mission of protecting Versemyst burning bright in their hearts. 
The Archmage, a wise and revered leader, steps forward to address the assembly.

"Listen, brave Guardians," the Archmage begins, "our world, Versemyst, is on the brink of great change. Legends speak of a mystical material known as Verseium, which possesses unimaginable power. 
It is our duty to ensure that this power is harnessed responsibly, for the good of all."

The Guardians lean in, their eyes filled with curiosity and determination. 
They had heard whispers of an incredible technology called Zero-Knowledge Proofs, and now the Archmage would shed light on its importance.

"Zero-Knowledge Proofs," the Archmage continues, "are the key to interacting with the Verseium while keeping its secrets hidden from prying eyes. 
Imagine being able to harness its magic without revealing its true nature to those who seek to abuse its power."

The Guardians exchange glances, their interest piqued. The Archmage explains further, painting a vivid picture of the concept.

"With Zero-Knowledge Proofs, we can prove the validity of a statement without revealing any underlying information. 
Picture this: we have a statement, a secret knowledge, and a challenge. Using Zero-Knowledge Proofs, we can convince others that we possess the secret knowledge without actually disclosing it."

One Guardian raises a hand, seeking clarification. "Archmage, how does this work? How can we prove something without revealing the proof itself?"

The Archmage smiles, his eyes twinkling with wisdom. "Ah, my brave apprentice, it is a dance of trust and ingenuity. 
Picture a scenario where one Guardian, the prover, possesses the secret knowledge, while another Guardian, the verifier, challenges their claim. Through a series of interactive exchanges, the prover demonstrates their knowledge without ever explicitly sharing it."

The Guardians nod, beginning to grasp the concept. They see how this technology aligns with their mission to protect the Verseium.

"The beauty of Zero-Knowledge Proofs," the Archmage adds, "is that they allow us to verify the truth of a statement without divulging unnecessary information. 
We can interact with the Verseium, accessing its powers covertly while guarding its mysteries against those who seek to exploit it."

Inspired and enlightened, the Guardians of Lumos eagerly await the next step in their journey. They now understand the fundamental concepts of Zero-Knowledge Proofs, and with this knowledge, they are one step closer to harnessing the incredible potential of the Verseium for the greater good of Versemyst.


## Components of a proof: Statement, Challenge, and Secret Knowledge. 🏰🏰🏰🏰

The Archmage continues to elucidate the intricacies of Zero-Knowledge Proofs, delving deeper into the components of a proof: the statement, challenge, and secret knowledge.

"Imagine a statement," the Archmage begins, "as a claim that we wish to prove to others without revealing the details behind it. 
It could be a statement about a hidden treasure, a forgotten incantation, or even the nature of the Verseium itself. 
This statement forms the core of our Zero-Knowledge Proof."

He pauses for a moment, allowing the Guardians to absorb the information before proceeding. 
Then, he continues, "Now, let's introduce the challenge. The challenge is a series of questions or requests made by the verifier—the one seeking proof of the statement. 
These challenges are designed to test the prover's knowledge without explicitly extracting the secret information."

The Guardians exchange glances, beginning to envision how this dance of proof unfolds. The Archmage takes a deep breath and continues to demystify the process.

"As for the secret knowledge, it is the key ingredient held by the prover. 
This knowledge substantiates the truth of the statement. However, the goal is to convince the verifier of the statement's truth without explicitly revealing the secret knowledge itself. It is a delicate balance between demonstrating one's understanding of the statement while maintaining the secrecy of the underlying information."

The Guardians nod, their minds swirling with newfound understanding. 
They see how this dance of proof preserves the secrecy of vital knowledge, safeguarding it against the prying eyes of the Coven of Shadows.

"Together," the Archmage concludes, "the statement, challenge, and secret knowledge form the foundation of a Zero-Knowledge Proof. 
It is through this dance of interaction and trust that we can convince others of the validity of our claims without compromising the integrity of the Verseium's secrets."

The Guardians feel a surge of excitement and purpose. They comprehend that mastering Zero-Knowledge Proofs will be the key to unlocking the full potential of the Verseium and ensuring its power is wielded responsibly. With this knowledge, they are equipped to continue their journey, unraveling the depths of Zero-Knowledge Proofs and safeguarding the Verseium from those who would misuse it.

## Primer on witness

A witness, in the context of Zero-Knowledge Proofs, is additional information or evidence that can be provided by the prover to convince the verifier of the truthfulness of the statement being proven. The witness is not the secret knowledge itself but can be related to it.

In a Zero-Knowledge Proof, the prover aims to convince the verifier that they possess knowledge of a statement's truth without revealing the actual secret information. The witness serves as supporting evidence that the prover possesses this knowledge.

To illustrate this concept, let's continue our story in the realm of Versemyst:

As the Guardians of Lumos delve deeper into their studies of Zero-Knowledge Proofs, the Archmage enlightens them about the significance of witnesses in the proof process.

"Witnesses," the Archmage explains, "are like the guardians of knowledge within a Zero-Knowledge Proof. They provide additional evidence that strengthens the prover's claim without exposing the secret information directly."

The Guardians listen intently, their curiosity piqued by this new dimension of understanding.

"For example," the Archmage continues, "let's imagine a Zero-Knowledge Proof where the prover wishes to demonstrate knowledge of a hidden inscription. The statement could be about the location of a hidden chamber or the unlocking of a mystical artifact. The witness, in this case, could be an ancient key or a specific incantation known only to the prover."

The Guardians envision the scene, picturing a wizard holding an ornate key or chanting an arcane phrase, further bolstering the credibility of the proof.

"The witness," the Archmage emphasizes, "is not the secret information itself but serves as supporting evidence, reinforcing the prover's knowledge and building trust with the verifier."

The Guardians nod in understanding, recognizing the importance of witnesses in the intricate dance of Zero-Knowledge Proofs.

"Remember," the Archmage concludes, "the witness, along with the statement, challenge, and secret knowledge, contributes to the holistic proof, providing a more compelling case while maintaining the confidentiality of the actual secret information."

Empowered with this knowledge, the Guardians continue their studies, now aware of the role witnesses play in the tapestry of Zero-Knowledge Proofs. They delve into deeper realms of cryptography, uncovering more intricate techniques and protocols to protect the Verseium's secrets.

Armed with their understanding of witnesses, the Guardians are prepared to employ these additional elements within their proofs, further enhancing the strength and trustworthiness of their assertions. They recognize that witnesses bring an additional layer of assurance, allowing them to convince verifiers without compromising the secrecy of the Verseium's hidden knowledge.

And so, the Guardians of Lumos embark on a journey to explore the realms of witnesses, armed with their newfound understanding of Zero-Knowledge Proofs. With each step, they strengthen their grasp on the delicate balance between proof and confidentiality, ensuring that the Verseium's secrets remain safeguarded and its power remains wielded responsibly.

## Mathematical Example

The protocol for the zero-knowledge proof works as follows:

1. Alice chooses a random number, x.
2. She computes y = 13x.
3. She sends y to Bob.
4. Bob checks that y is divisible by 13. If it is not, he rejects the proof. Otherwise, he proceeds to the next step.
5. Bob asks Alice to prove that she knows x. Alice does this by performing the following calculation:

```
z = y - 13x
```

6. Alice sends z to Bob.
7. Bob checks that z is 0. If it is, he accepts the proof. Otherwise, he rejects it.


In this example, Alice does not reveal the secret number 13 to Bob at any point in the protocol. However, Bob is able to verify that Alice knows the number, by checking that her calculations are correct. This is an example of a zero-knowledge proof, because Bob learns nothing about the secret number 13, other than the fact that Alice knows it.

To understand why this is a zero-knowledge proof, consider what would happen if Alice did not know the secret number 13. In this case, she would not be able to calculate z correctly. Bob would then be able to reject the proof, even though Alice would have successfully convinced him that she knows the secret number.

This shows that Alice must actually know the secret number in order to pass the zero-knowledge proof. However, Bob does not learn anything about the secret number, other than the fact that Alice knows it. This is why the proof is called "zero-knowledge".




