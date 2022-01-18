<img src="./graphic.svg" width="100%">

The process consists of 3 scripts.

The first script is a minting policy <b>X</b> that creates a one time thread token that is sent to a script output of the validator script <b>Y</b>.

The validator <b>Y</b> is a state machine and increases a counter id after each mint.

The actual mint happens in a seperate minting policy <b>Z</b>. The mint only happens if the state machine <b>Y</b> successfully transitioned and the token name includes the correct counter id.

After burning the thread token no more NFTs can be minted. The supply can also be capped regardless of the tread token being still in existence or not.

The NFTs can be natively burnt.
