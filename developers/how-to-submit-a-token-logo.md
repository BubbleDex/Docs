# 🐘 How to submit a token logo

When submitting the token icon, please select the corresponding link on Github according to the token type, and then submit the token icon and information file (Note: If the token information file is not submitted, it will not pass)

**Precautions:‌**

1. <mark style="color:red;">The link to burn the BUBBLE hash value and the link to verify the address must be attached;</mark>
2. <mark style="color:red;">A github account is not allowed to submit multiple logo applications;</mark>
3. <mark style="color:red;">The number of BUBBLE burned is 300;</mark>
4. <mark style="color:red;">Pool liquidity is greater than 50 ETH (except for special value);</mark>
5. <mark style="color:red;">Due to the openness of Github, anyone can leave a message in the submitted order, so please do not trust the comments of any third-party personnel, and beware of scams.</mark>
6. <mark style="color:red;">The token display logo is only to enrich the token information, and does not guarantee the absolute security of the token, nor does it represent any investment advice from Bubbleswap, please pay attention to the risks!</mark>



**The required information is as follows:**

**1.Token Icon**

{% code title="Require" %}
```
File extension: png, do not capitalize PNG
File name: logo.png
Size: 256px X 256px
Icon Background: A transparent background is recommended
```
{% endcode %}

**2.Token Information File**

{% code title="Require" %}
```
File extension: json, do not capitalize JSON
File name: info.json
```
{% endcode %}

Content: The following information must be included in the info.json file, please make sure the details are correct and follow the format requirements. The contract address should follow the checksum address format (please refer to the example below).

**Note: If the file format is incorrect, it will not pass the audit!**

```
{
 "name": "Bubbleswap",
 "website": "https://bubbleswap.co/",
 "description": "BUBBLE as the value-defining platform currency of Bubbleswap.",
 "explorer": "https://etherscan.com/token/0xF602F62037788DA57E583997c9480E0e80682743",
 "type": "ERC20",
 "symbol": "BUBBLE",
 "decimals": 18,
 "status": "active",
 "id": "0xF602F62037788DA57E583997c9480E0e80682743"
}
```

**3.Combustion process**

Burning process: When submitting a token icon, burn 300 BUBBLE to verify the legitimacy of your address. It should be noted that it cannot be returned after burning. Please consider carefully before burning.

{% tabs %}
{% tab title="Burning address" %}
0x000000000000000000000000000000000000dEaD
{% endtab %}

{% tab title="BUBBLE token contract address" %}
0xF602F62037788DA57E583997c9480E0e80682743
{% endtab %}
{% endtabs %}

{% hint style="danger" %}
Note: Please confirm again before transfer, because the receiving address is a black hole address and cannot be returned!
{% endhint %}

****

**Steps to submit a token icon:**

After the above information is completed, the token icon and information file can be added on GitHub.

**1.**Create a folder named after the token's contract address (Checksum format), and add the info.json and logo.png files to the folder;‌

Note: The file names must be: info.json and logo.png

**2.**Open the browser, enter GitHub, click "Fork" in the upper right corner and wait for creation

**3.** Drag the folder created in step 1 to the page in step 3‌,

4.Fill in the token information and burning hash address at "Commit changes" and fill in the description, then click "Commit changes"

**5.**The page will automatically return to the previous level, then click"Pull requests"

**6.** Click "Create a pull request"

**7.** The page will display the details you submitted, then click "Create pull request"

**8.** After entering the title and content, click "Create pull request"

**9.** At this point, you have successfully submitted your Pull request, and the administrator will review your request as soon as possible. ‌

### How to pass the application?

1. There is no counterfeiting or fraudulent behavior in the token project
2. Detailed token information

### Disclaimer

The Bubbleswap team allows anyone to submit a token application to the original warehouse. However, this does not mean that we have a direct partnership with all projects. ‌

After careful review, if fraudulent projects are found, the Bubbleswap team will reject them. The Bubbleswap team reserves the right to change the terms at any time due to changing market conditions, such as any identified risk of fraud or other risk factors.

Submitting token icons through GitHub is the only channel officially designated, and the Bubbleswap team is not responsible for any fraudulent token icons submitted through other channels.

### How long does the audit take?

After further verification by the administrator, the merge will be requested. If there are any other needs or changes, the information on the chain will prevail. ‌

Once the admin has merged the pull request, the token's icon can be updated. <mark style="color:orange;">Please Do not submit pull requests repeatedly!</mark> Thank you for your patience. ‌‌‌
