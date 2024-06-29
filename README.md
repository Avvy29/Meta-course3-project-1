
<h1>VERIFICATIONCONTRACT SMART CONTRACT</h1>

<h2>Introduction</h2>
<p>
    'VerificationContract' is a Solidity smart contract designed to handle value storage and division operations with error checking. It utilizes the require(), assert(), and revert() statements to ensure data integrity and proper operation.
</p>

<h2>Features</h2>
<ol>
    <li><b>Value Storage</b>: Allows updating and retrieval of a stored integer value.</li>
    <li><b>Safe Division</b>: Performs division with checks to prevent division by zero and ensures divisibility.</li>
</ol>

<h2>Public Variables</h2>
<ol>
    <li><b>currentValue</b>: Stores an integer value that can be updated via the contract.</li>
</ol>

<h2>Functions</h2>
<h3>modifyValue(uint newValue)</h3>
<p>
    Updates the stored integer value with a new positive integer.
</p>

<h3>calculateDivision(uint numerator, uint denominator)</h3>
<p>
    Divides the numerator by the denominator, with checks for zero and divisibility, and returns the result.
</p>

<h3>Parameters:</h3>
<ul>
    <li><b>newValue</b>: The new integer to store (must be greater than zero).</li>
    <li><b>numerator</b>: The integer to be divided.</li>
    <li><b>denominator</b>: The integer to divide by (must not be zero).</li>
</ul>

<h3>Conditions:</h3>
<p>
    <b>modifyValue:</b> Ensures that the new value is positive before updating.
    <br>
    <b>calculateDivision:</b> Requires the denominator to be non-zero and checks that the numerator is divisible by the denominator. Uses assert() to confirm the result's correctness.
</p>

<h2>Usage</h2>
<h3>Deploying the Contract</h3>
<ol>
    <li>Open the Remix IDE or another Solidity-compatible IDE.</li>
    <li>Copy and paste the contract code into a new Solidity file.</li>
    <li>Compile the contract using Solidity compiler version 0.8.1 or later.</li>
    <li>Deploy the contract to an Ethereum network (e.g., Ethereum mainnet, testnet, or local blockchain).</li>
</ol>

<h2>Authors</h2>
<p>
    Abhinav Vashisht
    <br>Vashishtabhinav2004@gmail.com</br>
</p>
```
