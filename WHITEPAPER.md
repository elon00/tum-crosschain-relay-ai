# TUM Cross-Chain Relay AI (`$TUMRELAY`) — Technical White Paper

## Abstract
Trustless light-client state relay and Merkle prover. Designed with high-throughput execution, post-quantum security vaults, and deterministic state guarantees.

## Tokenomics & Bonding Curve Formulation
The pricing function follows a continuous invariant curve:
$$P(S) = P_0 + m \cdot S$$

Where:
- $S$: Circulating supply.
- $P_0$: Initial base price.
- $m$: Linear slope parameter.

Total reserve required:
$$R(S) = \int_0^S P(x) \, dx = P_0 \cdot S + \frac{1}{2} m \cdot S^2$$
