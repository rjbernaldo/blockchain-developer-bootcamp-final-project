# Yet Another Auto Compounder
(Consensys Bootcamp Capstone Project)

## Goal & Preface
While very far from original, the main purpose of this project is to help myself get acquainted with the inner workings of auto compounding vaults by building one from scratch.

## Background
Liquidity mining has proven to be an effective way to incentivize users to provide liquidity for a protocol's native token.

Typically, users would supply two assets into an AMM and receive tokens often referred to as LP or liquidity provider tokens that represent their share of the total supply locked in that pool.

They would then send those tokens to a smart contract to receive another set of tokens that would represent their share of funds locked in that smart contract.

This smart contract would then continously mint (or buy) new reward tokens on each block that would be claimable by the LP.

## Opportunity
The rewards given out are often calculated on a per year basis and called APR. In order to maximize the returns, users can claim these rewards, create more LP tokens, and deposit them into the rewards pool effectively turning their APR into APY.

## Problem
While there are already a lot of auto compounders that exist today, a lot of them have evolved into complicated and vulnerable systems that have a lot of moving pieces and thus, have an ever increasing number of attack vectors.

## Solution
The focus of this capstone project is to create the simplest and easiest to understand auto compounder with as few dependencies as possible.

## Workflow
1. Users sign in using their metamask account
2. Users deposit LP tokens into an available vault
3. Users watch as their LP position grows.
4. Users withdraw and receive more LP tokens than they put in.
