![Banner](banner.jpeg)

# Welcome to SolSwipe! 🚀📱

## Who Are We? 🌟

SolSwipe is revolutionizing social media on the blockchain. Built on Solana, we offer a platform where creators can
share, engage, and earn in a fully decentralized environment. Say goodbye to manipulation and hello to a new era of
content creation and consumption!

## Features ✨

- **Create a Profile**: Create a new Solswipe user profile using just your Solana wallet! Set a custom display name and
  profile picture! Don't forget to update your bio and let the community know what your about!
- **Follow Users**: Get your friends on Solswipe and follow them using either wallet address to be the first to see
  their new Solswipe posts!
- **Post**: Upload your personalized Solswipe content with just the click of a button! Remember, you own every piece of
  content you post on Solswipe! If you want to remove a post, simply delete it and it will be removed from the Solana
  blockchain forever!
- **Comment**: Like your friends post? Let them know what you love about it by commenting on their posts!
- **Like**: Like other users posts!
- **Super Like**: Show your love by tipping creators with $swipes!
- **Personalization**: Enjoy content tailored just for you with our cutting-edge AI.
- **Earn**: Share in the revenue from all monetization activities simply by holding tokens!

## Updates 📅

Here, we'll share regular updates on our journey, including new features, partnerships, and milestones. Stay tuned!

### 🗓 April 25, 2024

![Contract Pagination](2024-04-25-01.png)
![Central Backend For Liking](2024-04-25-02.png)

*BIG UPDATES*:

1. Refactored the contract for initial beta release. Decided to move liking of posts and commenting to be off-chain
   since those can be stored centrally and will reduce impact on user as they won't have to accept a transaction and pay
   a gas fee for every like/comment. In addition, replaced previous constant post/follower/following size to be dynamic by switching from a vector based data structure to a linked list. This involves creating new accounts that act as "pages" to allow for a linked-list approach to fetching user posts and not limiting the number of followers, following or posts a user can have.
2. Created a small centralized backend API service to track and store likes and comments for posts. Unique identifiers are the PDA from the contract and only tracked items are the number of likes and the comments from users. 
3. Finalizing mobile web application as per our design teams initial figma design. Will be posting more updates on this over the next coming days before we begin roll-out of the beta application!

### 🗓 April 10, 2024

![Contract Testing With Dapp](2024-04-10.png)

Did some contract testing today with a quick boilerplate Dapp. Put together a simple UI using Material UI and developing
with React. Functionality is robust and we officially have posted the first post on Solswipe! (on devnet lol 😛). Will
continue adding some more of our contract features to this boilerplate as we anticipate our launch. UI team is hard at
work finalizing the remaining pieces of the actual Dapp design which we will integrate into our boilerplate.

## Get Involved 🤝

Want to contribute? Here's how you can be a part of our journey:

- **Developers**: Help us enhance the platform by contributing code.
- **Creators**: Create engaging content and grow with us.
- **Supporters**: Spread the word and help us revolutionize social media.

## Connect With Us 📬

- [Twitter](#)
- [Instagram](#)
- [Discord](#)

Join us on this incredible adventure to democratize social media, powered by blockchain. Let's make history together
with SolSwipe!