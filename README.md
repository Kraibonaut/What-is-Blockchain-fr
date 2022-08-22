# Level 1 - What is Blockchain?
![](https://i.imgur.com/Pn1B0t8.png)

Une blockchain est une base de données partagée, distribuée et permanente entre plusieurs nœuds sur un réseau informatique. Elles enregistrent les données d'une manière qui rend impossible, de manière probabiliste, la modification ou le piratage du système.

Plus précisément, comme son homonyme, la blockchain enregistre les données sous la forme d'une chaîne de blocs. Chaque bloc contient un groupe de transactions, qui peuvent consister à transférer des actifs sur le réseau ou à mettre à jour les informations stockées sur la blockchain.

Les chaînes de blocs ont été popularisées par la personne (ou le groupe) anonyme Satoshi Nakamoto, lorsqu'il a lancé le [Réseau Bitcoin](https://bitcoin.org) en 2008. Le bitcoin est un réseau de crypto-monnaies, qui gère principalement le transfert de l'actif BTC à travers le réseau, sans intermédiaire ou autorité de confiance, tout en garantissant que le réseau lui-même est sécurisé et ne peut pas être piraté (P.S. Le réseau bitcoin est aussi probablement la plus grande prime de bug au monde - si vous pouvez le pirater, vous devenez instantanément trillionnaire).

<Quiz questionId="25642ab6-6359-4d96-b361-9bcda3924821" />

Au fil du temps, la conception du bitcoin a inspiré d'autres réseaux blockchain plus performants, comme [Ethereum] (https://ethereum.org). Nous en apprendrons beaucoup sur Ethereum au cours des prochaines sessions.

<Quiz questionId="aa97ba07-0129-461a-a162-c10f029d26c6" />

### State Management

![](https://i.imgur.com/VQySjQu.png)

Les blockchains commencent par un état de genèse lors de leur lancement. L'état de genèse de Bitcoin a eu lieu en 2009, lors du lancement du réseau public. L'état de genèse d'Ethereum s'est produit en 2015, lors de son lancement.

Chaque transaction sur une blockchain modifie l'état global qui est répliqué sur tous les nœuds. 

<Quiz questionId="d2cb1910-40ac-481a-bf64-b117fe029182" />

![](https://i.imgur.com/wjK9Foy.png)

Comme il y a des millions de transactions, celles-ci sont regroupées en blocs. D'où le nom. Ces blocs sont enchaînés ensemble d'une manière cryptographiquement vérifiable afin qu'ils soient historiquement traçables. L'état actuel d'un réseau peut être recalculé à tout moment en partant du bloc de genèse et en faisant évoluer l'état en fonction des informations de chaque bloc jusqu'à présent.

<Quiz questionId="c7163d6f-a474-460d-93f8-ab11e6253af4" />

### Nodes

Un réseau de blockchains est géré de manière autonome par un réseau distribué [peer-to-peer] (https://fr.wikipedia.org/wiki/Pair-%C3%A0-pair) de nœuds informatiques. Sans entrer dans les détails, on peut simplement considérer que chaque nœud du réseau conserve une copie du grand livre des transactions mondiales. Par conséquent, chaque nœud peut vérifier et contrôler individuellement les transactions effectuées sur le réseau et s'assurer qu'il n'y a pas eu de comportement illicite.

Un autre type de nœud, appelé un [mining node](https://en.wikipedia.org/wiki/Bitcoin#Mining), Le mineur est chargé de regrouper les nouvelles transactions effectuées sur un réseau en un bloc, de les vérifier et de proposer à tous les autres d'inclure le bloc dans le grand livre mondial. Le minage est un processus difficile sur le plan informatique et il est très important de le faire en toute sécurité, c'est pourquoi les mineurs dont les blocs sont acceptés reçoivent une récompense symbolique pour leur travail.

<Quiz questionId="a96d92ca-5044-4d9e-b4c7-b094370a307f" />

<Quiz questionId="cda75960-e266-4deb-b317-20ccdcae9b98" />

L'utilisation d'une blockchain confirme que chaque unité de valeur n'a été transférée qu'une seule fois, et les mécanismes ingénieux mis en place par Satoshi Nakamoto ont résolu le problème de longue date de la décentralisation. [double-spending](https://en.wikipedia.org/wiki/Double-spending).

<Quiz questionId="229ed272-9cd3-4b42-936d-871cb2cfac3d" />

### Decentralization
En stockant les données dans un réseau de nœuds d'égal à égal, la blockchain est un réseau décentralisé. Cela présente des avantages considérables par rapport à l'approche traditionnelle consistant à stocker les données de manière centralisée. Il existe des exemples significatifs de problèmes liés à la centralisation - dont nous allons énumérer quelques-uns ici :

- Les violations de données dans les systèmes centralisés exposent de nombreuses données
- Les autorités centralisées peuvent censurer et couper la parole.
- La dépendance à l'égard d'une autorité centrale signifie que les problèmes en amont affectent les consommateurs en aval (par exemple, si AWS tombe en panne, la majeure partie de l'internet tombe aussi en panne).

<Quiz questionId="156de364-a10f-49fd-a669-05f3762dbab1" />

D'autre part, la décentralisation apporte les avantages inverses.
- Pas de censure car il n'y a pas d'autorité ou d'intermédiaire qui puisse vous censurer.
- Pas de temps d'arrêt car le réseau global fonctionne sur des milliers de nœuds à travers le monde.
- Résistance élevée aux attaques, ce qui rend impossible la manipulation ou la destruction des données.


### Use Cases

- Cryptocurrency
- Smart Contracts
- Decentralized Finance
- Gaming
- Supply Chain Tracking
- Counterfeiting Protection
- Data Privacy
- Decentralized Governance
- Verifiable ownership of assets

et bien d'autres encore...

<Quiz questionId="694123d0-2716-463c-9f14-bb838b02a971" />

### Resources

Pour en savoir plus sur les blockchains, nous vous conseillons vivement les ressources suivantes :

#### Must Watch
- [But how does bitcoin actually work? by 3Blue1Brown](https://www.youtube.com/watch?v=bBC-nXj3Ng4)
- [Blockchain Demo by Anders Brownworth](https://andersbrownworth.com/blockchain/)

<Quiz questionId="faf19815-bb85-4e21-80aa-e2f7cb1bd6b7" />

#### Recommended
- [A Gentle Introduction to Blockchain Technology by Bits On Blocks](https://bitsonblocks.net/2015/09/09/gentle-introduction-blockchain-technology/)
- [How does a blockchain work by Simply Explained](https://www.youtube.com/watch?v=SSo_EIwHSd4)

<SubmitQuiz />
