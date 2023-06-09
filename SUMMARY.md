# Table of contents

* [Introduction](README.md)
    * [Spec status](introduction/spec-status.md)
    * [Architecture diagrams](introduction/architecture-diagrams.md)
    * [Key concepts](introduction/key-concepts.md)
    * [Filecoin VM](introduction/filecoin-vm.md)
    * [System decomposition](introduction/system-decomposition.md)
* [Systems](systems/README.md)
    * [Filecoin nodes](systems/filecoin-nodes.md)
    * [Files and data](systems/files-and-data.md)
    * [Virtual machine](systems/virtual-machine.md)
    * [Blockchain](systems/blockchain.md)
    * [Token](systems/token.md)
    * [Storage mining](systems/storage-mining.md)
    * [Markets](systems/markets.md)
* [Libraries](libraries/README.md)
    * [Drand](libraries/drand.md)
    * [IPFS](libraries/ipfs.md)
    * [Multiformats](libraries/multiformats.md)
    * [IPLD](libraries/ipld.md)
    * [Libp2p](libraries/libp2p.md)
* [Algorithms](algorithms/README.md)
    * [Expected consensus](algorithms/expected-consensus.md)
    * [Proof-of-Storage](algorithms/proof-of-storage.md)
    * [Stacked DRG Proof of Replication](algorithms/stacked-drg-proof-of-replication.md)
    * [BlockSync](algorithms/blocksync.md)
    * [GossipSub](algorithms/gossipsub.md)
    * [Crytographic primitives](algorithms/crytographic-primitives.md)
    * [Verified clients](algorithms/verified-clients.md)
    * [Filecoin CryptoEconomics](algorithms/filecoin-cryptoeconomics.md)
* [Glossary](glossary/README.md)
    * [Account actor](glossary/account-actor.md)
    * [Actor](glossary/actor.md)
    * [Address](glossary/address.md)
    * [Ask](glossary/ask.md)
    * [Blockchain](glossary/blockchain.md)
    * [Block height](glossary/block-height.md)
    * [Block](glossary/block.md)
    * [Block reward](glossary/block-reward.md)
    * [Bootstrapping](glossary/bootstrapping.md)
    * [Capacity commitment](glossary/capacity-commitment.md)
    * [Challenge sampling](glossary/challenge-sampling.md)
    * [CID](glossary/cid.md)
    * [Client](glossary/client.md)
    * [Collateral](glossary/collateral.md)
    * [Consensus fault slashing](glossary/consensus-fault-slashing.md)
    * [Consensus](glossary/consensus.md)
    * [Cron actor](glossary/cron-actor.md)
    * [Deal](glossary/deal.md)
    * [Deal quality multiplier](glossary/deal-quality-multiplier.md)
    * [Deal weight](glossary/deal-weight.md)
    * [Drand](glossary/drand.md)
    * [Election](glossary/election.md)
    * [Election proof](glossary/election-proof.md)
    * [Epoch](glossary/epoch.md)
    * [Fault](glossary/fault.md)
    * [File](glossary/file.md)
    * [Filecoin](glossary/filecoin.md)
    * [Filecoin virtual machine (FVM)](glossary/filecoin-virtual-machine-fvm.md)
    * [FIL](glossary/fil.md)
    * [Finality](glossary/finailty.md)
    * [FR32](glossary/fr32.md)
    * [Gas and gas fees](glossary/gas-and-gas-fees.md)
    * [Genesis block](glossary/genesis-block.md)
    * [Ghost](glossary/ghost.md)
    * [Height](glossary/height.md)
    * [Init actor](glossary/init-actor.md)
    * [Lane](glossary/lane.md)
    * [Leader](glossary/leader.md)
    * [Leader election](glossary/leader-election.md)
    * [Message](glossary/message.md)
    * [Miner](glossary/miner.md)
    * [Multisig actor](glossary/multisig-actor.md)
    * [Node](glossary/node.md)
    * [On-chain off-chain](glossary/on-chain-off-chain.md)
    * [Payment channel](glossary/payment-channel.md)
    * [Piece](glossary/piece.md)
    * [Pledge storage](glossary/pledge-storage.md)
    * [Power](glossary/power.md)
    * [Power fraction](glossary/power-fraction.md)
    * [Power table](glossary/power-table.md)
    * [Proof-of-Replication (PoRep)](glossary/proof-of-replication-porep.md)
    * [Proof-of-Spacetime (PoSt)](glossary/proof-of-spacetime-post.md)
    * [Protocol](glossary/protocol.md)
    * [Proving period](glossary/proving-period.md)
    * [Proving set](glossary/proving-set.md)
    * [Quality-adjusted-power](glossary/quality-adjusted-power.md)
    * [Randomness](glossary/randomness.md)
    * [Randomness ticket](glossary/randomness-ticket.md)
    * [Raw byte power](glossary/raw-byte-power.md)
    * [Repair](glossary/repair.md)
    * [Retrieval miner](glossary/retrieval-miner.md)
    * [Reward actor](glossary/reward-actor.md)
    * [Round](glossary/round.md)
    * [Seal](glossary/seal.md)
    * [Sector](glossary/sector.md)
    * [Sectory quality multiplier](glossary/sector-quality-multiplier.md)
    * [Sector spacetime](glossary/sector-spacetime.md)
    * [Slashing](glossary/slashing.md)
    * [Smart contracts](glossary/smart-contracts.md)
    * [State](glossary/state.md)
    * [Storage fault slashing](glossary/storage-fault-slashing.md)
    * [Storage market actor](glossary/storage-market-actor.md)
    * [Storage miner actor](glossary/storage-miner-actor.md)
    * [Storage power actor](glossary/storage-power-actor.md)
    * [Ticket or VRF chain](glossary/ticket-or-vrf-chain.md)
    * [Tipset](glossary/tipset.md)
    * [VDF](glossary/vdf.md)
    * [Verified client](glossary/verified-client.md)
    * [Verified registry actor](glossary/verified-registry-actor.md)
    * [Voucher](glossary/voucher.md)
    * [VRF](glossary/vrf.md)
    * [Weight](glossary/weight.md)
    * [Window Proof-of-Spacetime (WindowPoSt)](glossary/window-proof-of-spacetime-windowpost.md)
    * [Winning Proof-of-Spacetime (WinningPoSt)](glossary/winning-proof-of-spacetime-winningpost.md)
    * [ZK-SNARK](glossary/zk-snark.md)
* [Appendix](appendix.md)
    * [Filecoin address](appendix/filecoin-address.md)
    * [Data structures](appendix/data-structures.md)
    * [Filecoin parameters](appendix/filecoin-parameters.md)
    * [Audit reports](appendix/audit-reports.md)
* [Filecoin Implementations](filecoin-implementations.md)
    * [Lotus](filecoin-implementations/lotus.md)
    * [Venus](filecoin-implementations/venus.md)
    * [Forest](filecoin-implementations/forest.md)
    * [Fuhon (cpp-filecoin)](filecoin-implementations/fuhon-cpp-filecoin.md)
* [Releases](releases.md)
    * [v2.1.1](releases/v2-1-1.md)
    * [v2.1.0](releases/v2-1-0.md)
    * [v2.0.0](releases/v2-0-0.md)
