# Voting Smart Contract

## Overview

The Voting smart contract allows users to register as voters, add candidates, and vote for their preferred candidates. It ensures secure and transparent voting, preventing double voting and allowing only registered voters to participate.

### Features

- **Voter Registration**: Only the contract owner can register voters.
- **Candidate Addition**: Only the contract owner can add new candidates.
- **Voting**: Registered voters can vote for their preferred candidates.
- **Results**: Retrieve the candidate with the highest votes.

## Usage

### Deployment

1. Deploy the contract to the Starknet blockchain.
2. Set the initial owner during contract deployment.

### Registering Voters

Only the owner can register voters using the `register_voter` function.

### Adding Candidates

Only the owner can add candidates using the `add_candidate` function.

### Voting

Registered voters can vote for candidates using the `vote` function. A voter can only vote once.

### Checking Results

- Use `get_candidate` to get candidate details.
- Use `get_candidate_vote` to get the vote count of a candidate.
- Use `winner` to get the candidate with the highest votes.

