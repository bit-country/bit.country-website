# Alpha-Testnet Release Notes

How to join alpha-testnet?

Please join our [Discord](https://discord.com/invite/PaMAXZZ59N), and increase your discord Rank by participating in the conversations, our community and support team constantly monior the ranks and will invite you to join alpha-testnet.


## v0.0.1.4
Summary
- Bunker - your personal space storing your own assets.
- Showroom - metaverse version of your local market place
- NFT - Royalty fees, Batch listing / transfer, favourite, trading activities, multi-types of NFT.
- Avatar - Skin color and performance improvement
- Sandpit - All outstanding bugs are fixed. Sky - more sky templates
- Various improvements. Please see details below

Details
- Stabilized asset gateway for depositing and withdrawing BIT.
- Support royalty fee for NFT Creator, earn royalty fee for each transaction on the local marketplace.
- Migrate the existing NFT collection to set the default loyalty fee.
- Implement minting fee when minting collection and NFT. 
- Improved My Assets page with filters to show purchased, created, listed, auction bids and favorites
- Users can favorite listings and non-listed assets so they can be viewed later in the my assets page
- Only allow metaverses with the Global NFT Search Crafted NFT to be able to list NFTs and collections in the Global NFT Search page. 
- Added a new section in the NFT listing page to see other auction/buy now listings of the same nft
- Added batch listing and transfer feature for multiples of the same nft
- Support new NFT types PDF, MP4, OGG
- Users can now see a list of the Metaverse followers
- Added activities tab under the collection page with filters
- User can click an activity item to see details page
- Displaying floor/ceiling price and volume traded for collections
- Added a “Go Back” functionality to the collection page
- Metaverse Settings page Global NFT Search option integrated
- NFT Authorization implemented. User will need to craft object and enable the feature to view collection listing requests
- One wallet, one account - if the user wants to switch wallets while logged in, they will need to authorize and link the new wallet -> sign process.
- Separated functionality for Metaverse Utility and Wallet Utility
- Released Bunker
  - Includes new model for bunker
  - Includes other environmental changes
  - Updated and improved block build handling
  - Updated and improved asset placement
- Fixed edge case with cancellation not restoring blocks
- Added pending preview for placed assets
- Improved asset preview resolves some model display issues
- Improved inputs on all tools
  - Resolved manual input errors on some inputs – e.g. couldn’t type 1.1 but only type 1
  - Resolved edge case where scaling broke aspect ratio for media items
  - Resolved rotation resetting on typewriter when changing scale
- Added close contextual button to tools to improve UX
- Resolved error on some skybox types
- Resolved error on some block and asset uploads
- Improvements to much of the UI to improve snappiness and more
- Improved advanced placement behaviour on all tools
- Improved API
  - Resolved edge cases when placing assets, texts and other items
  - Improved handling of block submissions – faster handling
- Updated lighting and configuration for graphical settings
- Resolved edge case behaviour related to collision detection toggling
- Improve edge case when creating some new skyboxes, blocks and models in ui
- Improve shadows for player, clothing and world
- Added 3D showroom to display the NFT in the marketplace.
- Improve the UI responsive of the avatar customizer
- Improve the Avatar skin color changing UI.
- Allow user to change their skin color back to the original skin.
- Allow user to reset their avatar wearable while editing the wearable.
- Reuse existing resources if they existed in the local environment instead of fetching the new item.
- Show warning when closing tab/window with unsaved changes
- Updated cost calculation for assets and models
- Allow environment customizer changes to persist in sandbox

## v0.0.1.3

- 2057819 Enhance asset selector and builder
- 72d0c90 Merge branch 'development/Master' into improvement/AssetSelectorAndBuilder
- 87776f6 Update ordering to add mesh to scene.
- 25e589d Add early break to retries wrapper.
- 356ac5b Display error notification
- 21740d3 Add different error message wording
- 9103cb7 Merge branch 'improvement/AssetSelectorAndBuilder' into development/Master
- bd8d63c Add new bunker.
- 807731e Calculate origin point using bounding box for highlighter
- cc484d6 Avoid adding origin offset everytime we show highlighter
- 88e9c5a Improve pending asset placement
- db8249f Merge branch 'development/Master' into improvement/AssetSelectorAndBuilder
- 64ce6db Revert change on scale Z
- d4d29bd Set rotation for preview mesh.
- b3b752d Fix collision issue
- e772371 Merge branch 'improvement/AssetSelectorAndBuilder' of into improvement/AssetSelectorAndBuilder
- c4171e3 Change to use bounding box unparented from mesh.
- 00153b0 Fix inability to type a value into scale and rotation.
- edc558c Fix error when clicking cancel after advanced placement
- 4884043 Update selected box after cancelling edit
- 9379df9 Fix issue with failure to load preview in model builder.
- d87f73d Migrate changes from placement context in asset selector to model builder.
- 7a1838a rename Spot to On-platform
- 9fa6b25 Fix error in same cases after placing a model from advanced placement
- 9b4cbaf Fix number as string
- 6782675 Add conditional for handling non-model meshes in pending meshes for model builder.
- a2fe3df reverse spot renaming
- 974cb94 Resolve edit issues after changing original scale value
- aa4246a Merge remote-tracking branch 'origin/development/Master' into improvement/AssetSelectorAndBuilder
- 43ba11e Reword from spot to on-platform
- 498bb4f Add quick change to allow other bunkers
- 470ee6d Fix pending mesh placement as per Vuk's work on other branch.
- 7fc4de4 Use latest bunker model.
- 7fa7a1a Add nft/listing favorites feature
- 3c2958c auction display improvements
- 23a3353 Remove double-slash on tutorial image src
- 37b5702 Merge branch 'development/Master' into uat/Master
- d00971d Fix incorrect pending mesh preview placement
- defed09 Ensure we exit check early for other bunkers
- fa312db Fix incorrect pending mesh preview placement
- 214766d Ensure we exit check early for other bunkers
- 8caa961 Merge branch 'development/Master' into uat/Master
- e35770d Is Admin Feature added in the UI
- 3ebbfd0 Minor button style changed
- 909c5d0 Merge remote-tracking branch 'origin/development/Master' into ELEMENT_MATRIX
- 8db95b5 Merge pull request #296 from bit-country/ELEMENT_MATRIX
- 5db2106 Publish Draft tidyup
- 6b4446b Merge pull request #297 from bit-country/ELEMENT_MATRIX
- 0ee7541 update btn style
- 0d4ab62 update showroom style
- f6b6bc5 update avatar customizer style, typos;
- fb27f61 Listing component improvements
- 6dfa7ef remove debugger
- 4a9bdd0 added online model in bunker
- d614bc2 temp disabled sectorHide to show other avatars
- 3e5f98d merge from dev/Master
- 92f7e00 Merge pull request #298 from bit-country/development/Master

## v0.0.1.2 @ 22-May-2022

- 2c9f6e0 Improvements left menu metaverses showing all metaverses and scrollable
- 3169c3d Fix Withdraw Bit validation bug
- 23550d7 handle close modals for deposit and withdraw, fix antd hover input error color
- 2b15211 Menu Highlight on marketplace
- 9103425 Minor UI changes
- 71b4c91 Create Metaverse Object initial
- 003b8f9 Update Modal UI, Fixed some richMediaTool bugs, Fixed NFT trigger position issue
- 42411f1 handle transfer validation onBlur, change error message
- 6ed3052 Draft Feature
- a4c2adc Small issue on removing item from grid
- 618d224 fix bid and buy now, git merge issue
- 571bbc9 Fix grammer
- 77b8bd0 Add bounds to sandpit.
- d0d293c Update MiningRate.js
- 76f25f2 Add meshes to show boundary in sandpit
- 43dcc93 Stop building out of bounds for voxels
- 0124fc1 Update environment customiser to keep state in sandpit
- 873568a Fix ordering for setting environment in customiser.
- 41b48e0 remove global styling change for input background in case of conflicts
- 0f0229d Responsiveness of Wallet
- 9b43b4c Feature Setting & NFT Collection Utility
- e2519e7 bit campaign responsiveness
- e8d41d4 Move block selector to avoid contexts drawing over the menu
- 2cdabf0 Prevent leaving page with pending changes.
- fc8d0a5 Update wording
- 7d28d88 Include deposit event to tx history
