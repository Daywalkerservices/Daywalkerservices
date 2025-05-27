import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

export default function Portfolio() { return ( <div className="min-h-screen bg-gray-950 text-white px-4 py-8"> <header className="text-center mb-12"> <h1 className="text-4xl font-bold">Desmond Ovuvie Unuaworho</h1> <p className="text-xl mt-2 text-gray-400"> Web3 & Blockchain Developer </p> </header>

<section className="max-w-4xl mx-auto">
    <Card className="mb-8 bg-gray-900">
      <CardContent className="p-6">
        <h2 className="text-2xl font-semibold mb-2">About Me</h2>
        <p>
          I’m Desmond Ovuvie Unuaworho, a dedicated Web3 developer driven by innovation in
          blockchain technology. I build smart contracts, decentralized applications, and
          user interfaces that connect real-world utility with decentralized power. With each
          project, I aim to contribute meaningfully to the decentralized future.
        </p>
      </CardContent>
    </Card>

    <h2 className="text-3xl font-bold mb-4">Projects</h2>

    <div className="grid gap-6">
      <Card className="bg-gray-900">
        <CardContent className="p-6">
          <h3 className="text-xl font-semibold">Token Tracker Dashboard</h3>
          <p className="text-gray-400 mt-1">
            A sleek dashboard that tracks real-time prices and wallet balances of popular Ethereum-based tokens.
          </p>
          <p className="text-sm text-gray-500 mt-1">Tech: React, Ethers.js, CoinGecko API</p>
        </CardContent>
      </Card>

      <Card className="bg-gray-900">
        <CardContent className="p-6">
          <h3 className="text-xl font-semibold">Decentralized Voting DApp</h3>
          <p className="text-gray-400 mt-1">
            A secure and transparent voting system deployed on Ethereum testnet to demonstrate governance mechanisms.
          </p>
          <p className="text-sm text-gray-500 mt-1">Tech: Solidity, Hardhat, React</p>
        </CardContent>
      </Card>

      <Card className="bg-gray-900">
        <CardContent className="p-6">
          <h3 className="text-xl font-semibold">NFT Minting Platform</h3>
          <p className="text-gray-400 mt-1">
            A front-end minting site where users can connect their wallets, upload artwork, and mint NFTs on a testnet.
          </p>
          <p className="text-sm text-gray-500 mt-1">Tech: Solidity, Web3.js, IPFS</p>
        </CardContent>
      </Card>

      <Card className="bg-gray-900">
        <CardContent className="p-6">
          <h3 className="text-xl font-semibold">Smart Contract Showcase</h3>
          <p className="text-gray-400 mt-1">
            A curated collection of reusable smart contracts, hosted on GitHub, with inline documentation and test coverage.
          </p>
          <p className="text-sm text-gray-500 mt-1">Tech: Solidity, Hardhat</p>
        </CardContent>
      </Card>
    </div>

    <div className="mt-12">
      <h2 className="text-3xl font-bold mb-4">Contact</h2>
      <p>Email: <a href="mailto:unuavworhog@gmail.com" className="text-blue-400">unuavworhog@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/unuavworho-desmond-ovuvie-845a99280" className="text-blue-400" target="_blank">Profile</a></p>
      <p>GitHub: <a href="https://github.com/Daywalkerservices/Daywalkerservices.github.io" className="text-blue-400" target="_blank">Repository</a></p>
    </div>
  </section>
</div>

); }

