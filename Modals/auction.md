# Auction Modal

When our auction contract is created, we realized that we need an auction id to send. Therefore, we have created this modal to just serve this specific need.

It has 2 fields:

## auctionId
auctionId is a Number field and automatically generated by mongoose sequence.

## eventId
eventId is a Number field and is given to backend to match auction with events.