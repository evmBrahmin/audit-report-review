**Lessons from the report** 

- Check that the logic that occurs on-chain is matched by any off-chain logic and that the 2 line up appropriately
- Confirm that require statements have the intended effect and are not too strict nor not strict enough
- If a contract has an effect that lasts over very long durations (minting gobblers over the next 10 years), consider what that effect relies on and the impact that would occur if it was delayed (chainlink deprecating a contract and upgrading to a new version)
- Appendix defines their understanding of the project and the outcomes of its construction (particularly the game theory aspects and what over optimization could result in)
- Thorough audit, appendix represents a deep understanding of the math of currency distribution and minting effects.
- Will be important to become more familiar with how the EVM manages data storage
- til that custom errors can be more gas efficient than a naked require statement
