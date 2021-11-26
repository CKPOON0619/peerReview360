# 360 Review visualisation
This project is produced as a demo for the visualisation of peer review within a company as a network.

## Major packages
- React
- D3
- React-d3-network
This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Background
In the company, peer review will be sent between co-workers as a feedback of their performance against different skills. In this demo, all these reviews are summarised using a modified pageRank algorithm. Each node carries certain amount of reference score according to the reference received from other nodes. 

There are 4 difference levels of inward reference, namely level 1 to 4, represented by red, yellow, green, blue respectively.

The size of each node is scaled according to the overall valid references received from other nodes(inward edges) for all skills level.





