# nft-api-nodejs-example
This code will generate a collection, 4 NFTs, one sale phase and 2 price tiers. 

Install dependencies:
```
npm install
```

Run:
```
node app.js
```


The output will be something like this: 

```
...

Create sale phase
{
  id: '01g8040ezr5856aevy25sc6hqn',
  type: 'random',
  name: 'pre sale 1',
  active: true,
  reservation_time: 1800,
  total_tokens: 6,
  remaining_tokens: 6,
  price_tiers: [
    {
      id: '01g8040ezndyh3qvdej4wetjk1',
      name: 'Silver plan',
      price: 15000000,
      quantity: 1,
      supply: 1,
      token_sold_count: 0,
      payment_link: 'https://buy-staging.tangocrypto.com?q=test_eyJjb2xsZWN0aW9uX2lkIjoiMDFnODA0MGU2bWY1NXJud2tkMnlhM2Q3enciLCJwaGFzZV9pZCI6IjAxZzgwNDBlenI1ODU2YWV2eTI1c2M2aHFuIiwic3RhcnRfZGF0ZSI6IjIwMjItMDYtMDEiLCJlbmRfZGF0ZSI6IjIwMjItMTItMDEiLCJydWxlcyI6W10sInByaWNlIjoxNTAwMDAwMCwicHJpY2VfaWQiOiIwMWc4MDQwZXpuZHloM3F2ZGVqNHdldGprMSIsInF1YW50aXR5IjoxLCJzdXBwbHkiOjEsInR5cGUiOiJQaGFzZVNhbGUiLCJpc19yYW5kb20iOnRydWUsInRpdGxlIjoiVGFuZ28gQ29sbGVjdGlvbiAyMiIsInRjYyI6InFYK3BnSVJtNEJuYlVUdlJxc3hrTGJueUFhbCtCSDlMekRHcjErVFJoNXVTZFFQZCtXMHp0dUJ6QXl4c1BmZlFKUVBHekhVVXZvQXRHT21NbmJZVklYVEFOQjI1aVJFMWIwUCs3Yy80QXNKNDJ1aExsWEVnd2tqY1ZBZlZBZz09IiwibWF4X3R4X2ZlZSI6ODc2Mjc3LCJyZXNlcnZhdGlvbl90aW1lIjoxODAwLCJuZnRfY29zdCI6MzQ0ODJ9'
    },
    {
      id: '01g8040eznkyvkb8f7vswdfa35',
      name: 'Golden plan',
      price: 20000000,
      quantity: 2,
      supply: 1,
      token_sold_count: 0,
      payment_link: 'https://buy-staging.tangocrypto.com?q=test_eyJjb2xsZWN0aW9uX2lkIjoiMDFnODA0MGU2bWY1NXJud2tkMnlhM2Q3enciLCJwaGFzZV9pZCI6IjAxZzgwNDBlenI1ODU2YWV2eTI1c2M2aHFuIiwic3RhcnRfZGF0ZSI6IjIwMjItMDYtMDEiLCJlbmRfZGF0ZSI6IjIwMjItMTItMDEiLCJydWxlcyI6W10sInByaWNlIjoyMDAwMDAwMCwicHJpY2VfaWQiOiIwMWc4MDQwZXpua3l2a2I4Zjd2c3dkZmEzNSIsInF1YW50aXR5IjoyLCJzdXBwbHkiOjEsInR5cGUiOiJQaGFzZVNhbGUiLCJpc19yYW5kb20iOnRydWUsInRpdGxlIjoiVGFuZ28gQ29sbGVjdGlvbiAyMiIsInRjYyI6InFYK3BnSVJtNEJuYlVUdlJxc3hrTGJueUFhbCtCSDlMekRHcjErVFJoNXVTZFFQZCtXMHp0dUJ6QXl4c1BmZlFKUVBHekhVVXZvQXRHT21NbmJZVklYVEFOQjI1aVJFMWIwUCs3Yy80QXNKNDJ1aExsWEVnd2tqY1ZBZlZBZz09IiwibWF4X3R4X2ZlZSI6ODc2Mjc3LCJyZXNlcnZhdGlvbl90aW1lIjoxODAwLCJuZnRfY29zdCI6MzQ0ODJ9'
    }
  ],
  start_date: '2022-06-01',
  end_date: '2022-12-01',
  created_at: '2022-07-15T05:06:25.912Z',
  updated_at: '2022-07-15T05:06:25.912Z'
}
```

You can take the payment links and paste it on a browser and buy the token throught Tangopay. 
