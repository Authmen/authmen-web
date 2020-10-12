<template>
  <div>
    <div id="technology" class="tech-container">
      <div class="center-area-1228">
        <div class="center-area techs">
          <div class="tech-details">
            <div class="bg"></div>
            <h2 class="title-decorated">What are the major advantages?</h2>
            <!-- <div class="clearfix">
              <p class="trust">Issues</p>
              <p class="trust">Distributed trusted authority</p>
              <div class="trust-left">
                <p
                  v-for="item in IssuesAndDistributedLeft"
                  :key="item.name"
                  class="trust-child"
                >
                  {{ item.font }}
                </p>
              </div>
              <p class="trust-mobile trust">Distributed trusted authority</p>
              <div class="trust-right">
                <p
                  v-for="item in IssuesAndDistributedRight"
                  :key="item.name"
                  class="trust-child"
                >
                  {{ item.font }}
                </p>
              </div>
            </div> -->
            <div class="Techniques">
              <!-- <div class="Techniques-font">Techniques</div> -->
              <div>
                <ul>
                  <li>
                    1. More Efficient And Secure Storage
                    <br />
                    The design is exquisite and has stronger performance. It can
                    realize the fast blockchain storage and traceability scheme
                    corresponding to the key information system, and carry out
                    the storage and transmission based on the blockchain in the
                    process of data sharing.
                  </li>
                  <li>
                    2. Real Tamper Proof Technology
                    <br />
                    In a real sense, it can help users to achieve tamper proof
                    function, instead of storage that users can't control like
                    arweave. In addition, the key data of malicious tampering
                    can be found in time, and the false data and illegally
                    tampered malicious data can be found in the use process, and
                    can be repaired in time.
                  </li>
                  <li>
                    3. Wider Application Scenarios
                    <br />
                    It can provide efficient and convenient blockchain services
                    for enterprises and institutions, and directly manage data
                    through front-end pages. It can provide users with localized
                    deployment of blockchain system, with the help of its own
                    anti tamper, traceability, strong disaster recovery and
                    other features, it can save energy and improve efficiency
                    for enterprise data management.
                  </li>
                  <li>
                    4. Trusted Storage Node
                    <br />
                    With the combination of the security technology of Trias
                    trusted basic chain and Byzantine consensus algorithm after
                    blockchain optimization, it innovatively increases the
                    weight consensus proportion factor of reputation system,
                    greatly reduces the consensus computing cost of blockchain
                    node information, and accelerates the transmission speed of
                    data on the blockchain. By introducing the mechanism of
                    trusted computing, the storage nodes are given credit system
                    factors, which greatly reduces the consensus complexity of
                    consensus nodes, and improves the execution time of existing
                    distributed storage blockchain by more than 10 times.
                  </li>
                  <li>
                    Authmen adopts the three-layer computing power system based
                    on leviatom in Trias architecture, and the combination of
                    TEE trusted computing and zero knowledge proof technology to
                    complete the right confirmation and security protection of
                    distributed storage data.
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="tech-features">
            <div>
              <div>
                <img src="../assets/tech/icon_tech_crowdAthority@2x.png" alt />
              </div>
              <div>
                <h2>The trusted network</h2>
                <!-- <p class="InterlayerFont">Community-Driven</p> -->
                <p>
                  The trusted network constructed by Levitom layer of Trias
                  maintains a unique white list for each storage node, which can
                  prevent the loading of abnormal programs and effectively block
                  network security attacks. At the same time, HCGgraph is a
                  trusted computing technology based on heterogeneous TEE. With
                  the help of Gossip protocol, a "trusted acquaintance" network
                  is constructed between consensus nodes using different TEE
                  technologies, and a "conspiracy default" model of global nodes
                  is constructed to locate trusted nodes efficiently, which
                  makes consensus more efficient and cost-effective.
                </p>
              </div>
            </div>
            <div>
              <div>
                <img
                  src="../assets/tech/icon_tech_certificateContracts@2x.png"
                  alt
                />
              </div>
              <div>
                <h2>TEE</h2>
                <!-- <p class="InterlayerFont">Business Rules</p> -->
                <p>
                  At the same time, the TEE technology of Trias does not rely on
                  a single category of hardware, so it has stronger
                  compatibility. The use of TEE technology can verify and
                  protect the whole life cycle of the computer running
                  environment on the basis of the - 1 layer of the hardware
                  root. At the same time, under the TEE security defense model
                  of Trias, it becomes a new incentive oriented security model,
                  which allows the defender to actively contribute the defense
                  nodes and computing power of TEE, and get the corresponding
                  advantage economic stimulation according to the defense
                  contribution provided in the Trias security network. Through
                  the trusted computing of Trias, multi-party, remote and
                  heterogeneous data storage, sharing and computing can be
                  realized under the premise of maintaining data ownership and
                  privacy.
                </p>
              </div>
            </div>
            <div>
              <div>
                <img src="../assets/tech/icon_tech_inssuance@2x.png" alt />
              </div>
              <div>
                <h2>ZK-snarks</h2>
                <!-- <p class="InterlayerFont">Usage Scenarios</p> -->
                <p>
                  In addition, the data of trusted hardware and program based on
                  Trias can ensure that the information or data will not be
                  disclosed in the trusted program, and ZK-snarks are used to
                  ensure the privacy of the data.
                </p>
              </div>
            </div>
            <div>
              <div>
                <img
                  src="../assets/tech/icon_tech_certificateLedger@2x.png"
                  alt
                />
              </div>
              <div>
                <h2>Trusted Computing</h2>
                <!-- <p class="InterlayerFont">Trustworthiness of Sources</p> -->
                <p>
                  Through trusted computing, Authmen enables different tee
                  protocols to collect the latest status of neighboring nodes,
                  check and record historical information, and propagate the
                  results among other nodes through gossip protocol, and form a
                  reputation network. It repeatedly selects "the most difficult
                  point to lie" as its repeated function contract presentation,
                  forming a robust and efficient running environment, and
                  building a trusted computing based environment Based on the
                  blockchain distributed storage security network.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="Shelter"></div>
    <div class="works-container">
      <div class="line"></div>
      <h2 class="title-decorated title-web">HOW IT WORKS</h2>
      <p class="works-holder">
        The Trusted Storage Platform
      </p>
      <div class="work-box">
        <div class="WhiteShelter"></div>
        <div class="box-Differentiated">
          <div class="box-container">
            <div class="video-cover" @click="noneCover()" :style="videoShow?{ display: 'block'}:{ display: 'none' }"></div>
            <video
              poster="../assets/bg/img_video_bg.png"
              src="../video/200910.mp4"
              controls
              id="videoShow"
            ></video>
          </div>
        </div>
        <!-- <div class="Vimg">VIEW Image</div> -->
      </div>
      <div class="works-bg"></div>
    </div>
    <div class="SolutionsContainer">
      <div class="SolutionsContainerCeng"></div>
      <div class="Solution">
        <div class="PaddingModel">
          <div>
            <div class="HorizontalLine"></div>
            <h2 class="title-decorated">
              <b>
                Authmen's solution
              </b>
              <span
                >The Authmen's storage contains seven main functional
                modules:</span
              >
            </h2>
          </div>
        </div>
        <div
          class="PaddingModel ModelEleven"
          v-for="item in Solutions"
          :key="item.img"
        >
          <img :src="item.image" />
          <p class="TitleFont">{{ item.Boldfont }}</p>
          <p>{{ item.ComFont }}</p>
        </div>
        <div
          class="FuzzyGradualChange"
          :style="{
            background: show ? 'rgba(255, 255, 255, 0.6)' : 'rgba(0,0,0,0)'
          }"
        >
          <div class="Vimg VimgT" v-if="show" v-on:click="allShow()">
            VIEW ALL
          </div>
          <div class="Vimg Vimgf" v-if="!show" v-on:click="allshrink()">
            SHRINK All
          </div>
        </div>
      </div>
    </div>
    <div class="Usage">
      <div class="UsageContainer">
        <div class="ContainerLeft">
          <ul class="Eliminaterolling">
            <li
              v-for="item in UsageContainer"
              :key="item.font"
              :class="item.index == RedKey ? 'RedBg' : ''"
              @click="RedKey = item.index"
            >
              {{ item.font }}
              <div class="line"></div>
            </li>
          </ul>
        </div>
        <div class="ContainerRight">
          <div class="Hiddenarrow">
            <ul>
              <li
                v-for="item in Hiddenarrow"
                :key="item.index"
                :class="item.index == RedKey ? 'RedBg' : ''"
                :id="item.index == RedKey ? 'ShowDom' : ''"
              >
                <img src="../assets/misc/icon_misc_arrow@2x.png" alt />
              </li>
            </ul>
          </div>
          <div class="ContentModel">
            <div :id="RedKey === 1 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Token Metrics</b>
                <span></span>
              </h3>
              <div class="Fund">
                <ul>
                  <li>
                    Token ticketer: AUT
                  </li>
                  <li>
                    Total supply: 10,000,000 tokens (10million)
                  </li>
                  <li>
                    Testnet mining (Team and early contributors): 1,500,000 tokens (1.5million)
                  </li>
                  <li>
                    Reward for usage:5,500,000(5.5 million)
                  </li>
                  <li>
                    Lockdrop: 2,000,000 tokens:(2 million)
                  </li>
                  <li>
                    Liquidity provision: 500,000 tokens(0.5 million)
                  </li>
                  <li>
                    Bounce sale 500,000 tokens (0.5million)
                  </li>
                </ul>
              </div>
            </div>
            <div
              :id="RedKey === 2 ? 'ModelShow' : ''"
              :class="RedKey === 2 ? 'noList' : ''"
            >
              <div class="HorizontalLine"></div>
              <h3>
                <b>Lockdrop</b>
                <span></span>
              </h3>
              <div class="Fund">
                <ul>
                  <li>
                    AUT token will mirror Arweave block production. For each new Arweave block generation, there will be 1 AUT tokens being generated. New AUT tokens will be awarded every day to users of the protocol, based on TRY staking. Users can lockup their TRY tokens to get free AUT tokens. This will begin near product launch.
                    <p>
                      (Arweave block production information: Arweave block production: One block per 2 Minutes, 720 block per day, every block has 3 AR token reward, every day 2200 tokens.)
                    </p>
                  </li>
                </ul>
              </div>
            </div>
            <div
              :id="RedKey === 3 ? 'ModelShow' : ''"
              :class="RedKey === 3 ? 'noList' : ''"
            >
              <div class="HorizontalLine"></div>
              <h3>
                <b>Uniswap liquidity provision</b>
                <span></span>
              </h3>
              <div class="Fund">
                <ul>
                  <li>
                    We will open two pools on uniswap: AUT/ETH and AUT/TRY. We provide incentives for people to provide liquidity to the AUT/TRY uniswap pool. You can stake your LP tokens through Authmen and get AUT rewards. There will be 500,000 AUT rewards and it will be distributed throughout 60 days timeframe.
                  </li>
                </ul>
              </div>
            </div>
            <div
              :id="RedKey === 4 ? 'ModelShow' : ''"
            >
              <div class="HorizontalLine"></div>
              <h3>
                <b>Reward for usage</b>
                <span></span>
              </h3>
              <div class="Fund">
                <ul>
                  <li>
                    <b>Staking subscription: </b>
                    A subscription model is staking tokens for the service. Users can choose to stake (lock) at least 10 units of platform tokens for the premium service. A user can choose to unstake the token and end the subscription, or he can choose to keep staking. Subscription users do not lose the tokens after staking.
                  </li>
                  <li>
                    <b>Governance: </b>
                    The governance of Authmen websites will determine the storage providers of Authmen websites and maintain the dual diligence of the providers. The governance will also determine the application development and onchain governance parameters.
                  </li>
                </ul>
              </div>
            </div>
            <!-- <div :id="RedKey === 1 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>Decentralized PKI for Secure Authentication</span>
              </h3>
              <div class="PkiImg">
                <img src="../assets/usage/img_us_PKI.png" alt />
              </div>
            </div>
            <div :id="RedKey === 2 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>Defi: Fund Spending</span>
              </h3>
              <div class="Fund">
                <ul>
                  <li>
                    <p>
                      Actions for spending funds to be certified by community
                      members.
                    </p>
                    <p>
                      Will be provided through our Bitfreeze
                      (http://bitfreeze.io) solution by Threshold Multi-Party
                      Signatures (Threshold ECDSA).
                    </p>
                    <p>
                      MultiSig has been already using by Bitcoin and others.
                      However, MultSig has several issues regarding security,
                      privacy and scalability. Authmen will deploy Threshold
                      ECDSA eliminating all these issues.
                    </p>
                  </li>
                  <li>n parties.</li>
                  <li>Jointly compute a single public key.</li>
                  <li>Each party has a share of the secret key.</li>
                  <li>t parties needed to generate new signatures.</li>
                  <li>Signature:</li>
                </ul>
                <div>
                  <img src="../assets/usage/img_us_defi.png" alt />
                </div>
              </div>
            </div>
            <div :id="RedKey === 3 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>Reviewing</span>
              </h3>
              <div class="Reviewing">
                <div>
                  <h2>
                    <p>
                      Public accounts can anonymously review any process and can
                      get a reward if their review accepted as valuable.
                    </p>
                    <p>
                      Code quality and Decentralized Certification System:
                      Program source codes need to be certified for being
                      peer-reviewed or tested.
                    </p>
                  </h2>
                  <ul>
                    <li>
                      We can first issue certificates for developer IDs (like
                      expertise in C, Java, Python, Go, Rust with different
                      levels) and then get their assessment on program source.
                    </li>
                    <li>
                      In this way, we might have a valuable and universal
                      Certification system as well.
                    </li>
                  </ul>
                </div>
                <div>
                  <h2>
                    <p>
                      Document quality: Public documents (e.g. Wikipedia pages)
                      need to be certified for being peer-reviewed or verified.
                    </p>
                  </h2>
                  <ul>
                    <li>
                      This is also similar to code quality and will be very
                      valuable.
                    </li>
                    <li>
                      The rewarding mechanism and incentivizing users:
                      <ul>
                        <li>
                          The community members are free to fill the parameters.
                        </li>
                        <li>
                          This actually make Authmen a Public-chain, where
                          Certificate Contract can be written by the committee
                          to define the terms/conditions, issue/revocation for
                          different certificates satisfying their own
                          community's need.
                        </li>
                      </ul>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div :id="RedKey === 4 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>
                  Community Management: Certificates of Professional
                  <br />Experience Through Crowd
                </span>
              </h3>
              <div class="Crowd">
                <div>
                  <div>
                    <h3>Some Areas of Certification</h3>
                    <ul>
                      <li>
                        Computer technology (Software engineering, Information
                        technology)
                      </li>
                      <li>Accountancy, auditing and finance</li>
                      <li>Language education</li>
                      <li>Project management</li>
                    </ul>
                  </div>
                  <div>
                    <h3>Examples</h3>
                    <ul>
                      <li>Certified in the Governance of Enterprise IT</li>
                      <li>AWS Certified Solutions Architect</li>
                      <li>Project Management Professional (PMP)</li>
                      <li>AWS Certified Developer – Associate</li>
                      <li>
                        Certified Information Systems Security Professional
                        (CISSP)
                      </li>
                      <li>
                        Certified in Risk and Information Systems Control
                        (CRISC)
                      </li>
                      <li>Certified Information Security Manager (CISM)</li>
                      <li>Certified Scrum Master</li>
                      <li>Certified Ethical Hacker (CEH)</li>
                      <li>Microsoft Certified Solutions Expert (MCSE)</li>
                      <li>Certified Information Systems Auditor (CISA)</li>
                      <li>
                        Cisco Certified Networking Professional (CCNP) Routing
                        and Switching
                      </li>
                    </ul>
                  </div>
                </div>
                <div></div>
              </div>
            </div>
            <div :id="RedKey === 5 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>Reviewing: Secure Coding</span>
              </h3>
              <div class="Coding">
                <div class="CodingFont">
                  <div>
                    <p>
                      To prevent software vulnerabilities and manage version
                      control. (For example, we cannot only rely on GitHub
                      accounts’ passwords which are subject to online and
                      offline dictionary attacks.)
                    </p>
                    <p>
                      Consensus need to be made when merging codes, issuing
                      bugs/bug-fixes, adding/removing features etc.
                    </p>
                  </div>
                  <div>
                    <p>
                      Authmen builds crowd decisions, and certifies the
                      decisions for enforcement consistency checking or future
                      reference through threshold signatures by the development
                      team or manufacturer’s private signing key shares.
                    </p>
                  </div>
                </div>
                <div class="CodingImgF"></div>
                <button>Signing Code: Through Authmen Wallets</button>
                <div class="CodingFlex"></div>
                <button>
                  Verifying the Code Integrity: Retrieved from Authmen
                  Blockchain Network
                </button>
              </div>
            </div>
            <div :id="RedKey === 6 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>Polling: Authmen as a Public Bulletin Board</span>
              </h3>
              <div class="Board">
                <div>
                  <p>
                    Only anonymously certified accounts can vote for a member of
                    an organization or a citizen of a country.
                  </p>
                  <h2>Setup</h2>
                  <ul>
                    <li>
                      The votes will be encrypted using a (t,n)-threshold
                      homomorphic encryption scheme (together with ZK proofs)
                      like Threshold Paillier Public Key Encryption Scheme.
                    </li>
                    <li>
                      The encrypted votes will be published on the chain (which
                      is called “bulletin board” in the context of internet
                      voting) and no one can change or delete a from the chain
                      which ensures the integrity.
                    </li>
                    <li>
                      There is only one public key pk whereas the corresponding
                      secret key sk=(𝑠𝑘1, s𝑘2,...,𝑠𝑘𝑛) is shared between
                      different and independent organizations assuming at least
                      t out of them are honest and do not maliciously cooperate.
                    </li>
                  </ul>
                </div>
                <div>
                  <p>1. Download: The Voter Downloads Authmen Wallet.</p>
                  <p>
                    2. Registration: Request and registers for the election to
                    qualify. Authorized to cast a vote and issue an anonymous
                    certificate.
                  </p>
                  <p>
                    3. Voting: The voter votes and submits his ballot to Authmen
                    Blockchain Network (anonymously).
                  </p>
                  <p>
                    4. Verification: The voter can privately check and verify
                    whether their vote was cast as intended.
                  </p>
                  <p>
                    5. Tallying: Once the polling/voting process has been
                    finished the independent parties will collaboratively
                    perform partial decryption and finally get the results.
                  </p>
                </div>
              </div>
            </div>
            <div :id="RedKey === 7 ? 'ModelShow' : ''">
              <div class="HorizontalLine"></div>
              <h3>
                <b>Usage Scenarios -</b>
                <span>Crowd Witness: Blockchain in Fake Information</span>
              </h3>
              <div class="Information">
                <div>
                  <div></div>
                  <h4>The false news are related to:</h4>
                  <ul>
                    <li>Politics</li>
                    <li>Health</li>
                    <li>Vacation</li>
                    <li>Business</li>
                  </ul>
                </div>
                <div>
                  <div></div>
                  <h4>Attribute V:</h4>
                  <ul>
                    <li>Name (optional)</li>
                    <li>News agency license</li>
                    <li>Address proof</li>
                    <li>Domain name</li>
                    <li>Work permit</li>
                    <li>Years of working</li>
                  </ul>
                </div>
              </div>
            </div> -->
          </div>
        </div>
      </div>
    </div>
    <div id="team" class="team-container">
      <!-- <div class="center-area">
        <h2 class="title-decorated Core">CORE TEAM</h2>
        <div class="visible-pc fluid-container Eliminaterolling">
          <div class="member">
            <img src="../assets/team/img_team_nizamoglu@2x.jpg" alt />
            <h3>MEHMET NİZAMOĞLU</h3>
            <p>Co-Founder and CEO</p>
            <p class="AdFont">
              Since graduating in Industrial engineering in 2001 from Middle
              East Technical University Mehmet Nizamoglu gained unparalleled
              experience focusing on IT
            </p>
            <button v-on:click="detail('one')">DETAIL</button>
          </div>
          <div class="member">
            <img src="../assets/team/img_team_leoChen@2x.png" alt />
            <h3>Leo Chen</h3>
            <p>Co-Founder & COO</p>
            <p class="AdFont">
              Leo Chen has got his Master Degree in Computer Security from
              Peking University. Before founding Authmen, he had worked for the
              CCID (China Center for Information…
            </p>
            <button v-on:click="detail('two')">DETAIL</button>
          </div>
          <div class="member">
            <img src="../assets/team/img_team_noPhoto@2x.jpg" alt />
            <h3>Assoc. Prof. Mehmet Sabir Kiraz</h3>
            <p>Co-Founder & Chief Scientist</p>
            <p class="AdFont">
              Mehmet Sabır Kiraz has been currently working in De Montfort
              University, UK as an Assoc. Prof since Nov 2018. He worked as the
              director of Blockchain Research Lab at TUBITAK…
            </p>
            <button v-on:click="detail('three')">DETAIL</button>
          </div>
        </div>
      </div> -->
      <div class="center-area area">
        <div class="technology-box">
          <div class="line"></div>
          <h2>TECHNOLOGY PARTNERSHIP</h2>
          <div>
            <img class="partner-logo" src="../assets/logo_Trias@2x.png" alt />
          </div>
        </div>
        <div class="cover-bg">
          <div class="line"></div>
          <h2 class="title-decorated">
            INVESTOR
          </h2>
          <div>
            <img class="partner-logo" src="../assets/img_ngc_logo.png" alt />
          </div>
        </div>
      </div>
    </div>
    <div id="roadmap" class="roadmap-container">
      <div class="center-area-1228">
        <div class="title">
          <div class="bg"></div>
          <div>
            <h2>Roadmap</h2>
            <p>Authmen Milestone</p>
          </div>
        </div>
        <div class="roadmap-slick">
          <div class="slick-area">
            <div
              class="slick-item"
              v-for="item in roadmapItems"
              v-bind:key="item.date"
            >
              <div v-bind:class="['baseline', { up: item.isUp }]">
                <div class="left-line"></div>
                <div class="point">
                  <div class="rm-info" v-html="item.info"></div>
                  <div class="rm-date">{{ item.date }}</div>
                </div>
                <div class="right-line"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="updates" class="updates-container"></div>
    <div class="Footer">
      <div class="footer-main">
        <div class="computer">
          <div class="RLogo"></div>
          <!-- <ul>
            <li><a href="#authmen">home</a></li>
            <li><a href="#technology">Technology</a></li>
            <li><a href="#roadmap">Road Map</a></li>
          </ul> -->
        </div>
        <div>
          A trusted blockchain storage protocol
        </div>
        <div>
          <ul>
            <li>
              <a target="blank" href="https://t.me/authmen">
                <img src="../assets/social/icon_social_telegram@2x.png" alt />
              </a>
            </li>
            <li>
              <a target="blank" href="https://www.facebook.com/AuthmenBlockchain/">
                <img src="../assets/social/icon_social_facebook@2x.png" alt />
              </a>
            </li>
            <li>
              <a target="blank" href="https://medium.com/@authmen">
                <img src="../assets/social/icon_social_medium@2x.png" alt />
              </a>
            </li>
            <li>
              <a target="blank" href="https://twitter.com/home">
                <img src="../assets/social/icon_social_twitter@2x.png" alt />
              </a>
            </li>
          </ul>
        </div>
        <div class="pc">
          <div class="RLogo"></div>
          <!-- <ul>
            <li>Home</li>
            <li>Technology</li>
            <li>Team</li>
            <li>Road Map</li>
          </ul> -->
        </div>
        <div class="Gray-line"></div>
        <div class="Authmen">
          Copyright © 2020, All Right Reserved. Authmen Web.
        </div>
      </div>
    </div>
    <div id="BigHead-com">
      <div class="BigContainer">
        <div class="PcPic"><img :src="data.pic" /></div>
        <div class="ClickX" v-on:click="closeX()"></div>
        <div class="LineFo">{{ data.name }}</div>
        <div class="LineFt">{{ data.tit }}</div>
        <div class="LineFth">
          <p>
            {{ data.pfonto }}
          </p>
          <p>
            {{ data.pfontt }}
          </p>
        </div>
      </div>
    </div>
    <div id="BigHead-pc">
      <div class="BigContainer">
        <div class="PcPic"><img :src="data.pic" /></div>
        <div class="ClickX" v-on:click="closeX()"></div>
        <div class="LineFo">{{ data.name }}</div>
        <div class="LineFt">{{ data.tit }}</div>
        <div class="LineFth">
          <p>
            {{ data.pfonto }}
          </p>
          <p>
            {{ data.pfontt }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import $ from "jquery";
require("slick-carousel");

export default {
  name: "MainPart",
  data: function() {
    return {
      show: false,
      data: {
        name: "",
        tit: "",
        pfonto: "",
        pfontt: "",
        pic: ""
      },
      videoShow: true,
      UsageContainer: [
        {
          font: "Token Metrics",
          index: 1
        },
        {
          font: "Lockdrop",
          index: 2
        },
        {
          font: "Uniswap liquidity provision",
          index: 3
        },
        {
          font: "Reward for usage",
          index: 4
        }
        // {
        //   font: "Secure Coding",
        //   index: 5
        // },
        // {
        //   font: "Polling",
        //   index: 6
        // },
        // {
        //   font: "Crowd Witness",
        //   index: 7
        // }
      ],
      IssuesAndDistributedLeft: [
        {
          font: "01.The trusted party deanonymizes anonymous users."
        },
        {
          font: "02.Anonymity control mechanisms may be abused."
        },
        {
          font: "03.Dangers of a centralized trusted authority."
        },
        {
          font: "04.It may be attacked or corrupted."
        }
      ],
      IssuesAndDistributedRight: [
        {
          font: "01.Makes the system more robust against failure or attacks."
        },
        {
          font: "02.The trust on a single entity is reduced."
        },
        {
          font:
            "03.Several entities need to collaborate in order to identify a user."
        }
      ],
      Solutions: [
        {
          image: require("../assets/log/icon_solution_client@2x.png"),
          Boldfont: "Client tamper-proof module",
          ComFont:
            "This module provides protection for specified directories for clients. Once the blockchain tamper proofing service starts to protect the specified client directory, any tampering operation (adding, deleting, modifying, moving the directory or file) to the directory, namely the subdirectories and files contained in the directory will be automatically restored. If the monitored protected directory is maliciously deleted, the client tamper-proof module will automatically identify the logged in system user and force the user to log off.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_user@2x.png"),
          Boldfont: "User management module",
          ComFont:
            "This module mainly provides for the specified ordinary user to add a protected directory on the target host, to allocate the existing protected directory, and to cancel the operation authorization of the specified user to the directory.Only after the ordinary user is authorized to specify the operation permission of the directory, can it carry on the resource management.The administrator has permission to operate on all directories on all target hosts. In addition, the module provides the ability to freeze and enable ordinary users.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_file@2x.png"),
          Boldfont: "File management module",
          ComFont:
            "This module provides resource management capabilities for protected directories on the specified target host.Users can add, delete, move, and rename files and directories, each of which generates a new version record, one of two ways to manage resources under the directory.In addition, the module provides the ability to pause and start protection for the specified root directory. Only after the protection is paused can the user make a manual resource change directly on the target host.When protection is enabled, changes are automatically identified and a new version is formed.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_version@2x.png"),
          Boldfont: "Version information maintenance module",
          ComFont:
            "This module provides version information maintenance function to protect directory, view all historical version information, and provide version recovery function. Each time the user changes the file through the 8-component blockchain tamper-proof service, suspends the root directory protection manual changes, and restarts the tamper-proof service, the corresponding version record will be generated.",
          show: false
        },
        {
          image: require("../assets/log/icon_solution_monitor@2x.png"),
          Boldfont: "Tamper-proof status monitoring module",
          ComFont:
            "This module provides tamper-proof service status on the target host, and users can see the running status of all tamper-proof services deployed with eight-component blockchain.Running states include normal and heart rate timeout.",
          show: false
        },
        {
          image: require("../assets/log/icon_solution_log@2x.png"),
          Boldfont: "User operation log module",
          ComFont:
            "This module provides the function of viewing the operation log of users through the tamper-proof service of our blockchain.It mainly contains the user's boot/pause root protection, new, delete, move and rename operation records.",
          show: false
        },
        {
          image: require("../assets/log/icon_solution_client log@2x.png"),
          Boldfont: "Client tamper-proof log module",
          ComFont:
            "This module provides the ability to record tampering actions against protected directories on the target host.Monitored tampering includes adding, deleting, modifying, and moving directories or files.",
          show: false
        }
      ],
      roadmapItems: [
        {
          date: "2020 Q4",
          info: "Academic Research",
          isUp: true
        },
        {
          date: "2021 Q1",
          info: "CertLedger Team Setup",
          isUp: false
        },
        {
          date: "2021 Q1 - 2021 Q2 ",
          info: "Academic Study (White/Technical Paper)",
          isUp: true
        },
        {
          date: "2021 Q3. ",
          info: "Team Setup",
          isUp: false
        },
        {
          date: "2021 Q4",
          info: "White paper release. Website release. Token model.",
          isUp: true
        },
        {
          date: "2021 Q5.",
          info: "Smart contract development kick-off. Strategic partnership.",
          isUp: false
        },
        {
          date: "2021 Q6.",
          info:
            "Dev-milestone: Certificate registration & revocation. Certificate verification using SPV client. Cryptographic infrastructure development for Authmen board. Testnet release V1. 2020 Jan. Release candidate V1",
          isUp: true
        },
        {
          date: "2021 Q7.",
          info: "Release candidate V1 on testnet.",
          isUp: false
        },
        {
          date: "2021 Q8.",
          info: "Authmen token enters exchanges",
          isUp: true
        },
        {
          date: "2021 Q9.",
          info:
            "Authmen fullnode infrastructure release. Mobile wallet release. Fraud reporting infrastructure development. Testnet release V2. Reviewing and testing. ",
          isUp: false
        },
        {
          date: "2021 Q10.",
          info: "Release candidate V2 on Testnet ",
          isUp: true
        },
        {
          date: "2021 Q11 ",
          info: "Production release on V1 ",
          isUp: false
        },
        {
          date: "2021 Q12 ",
          info: "Authemen open to public for V1  ",
          isUp: true
        },
        {
          date: "2021 Q13 ",
          info: "Authemen to implement <br> 1 additional usage scenario.",
          isUp: false
        }
      ],
      Hiddenarrow: [
        {
          index: "1",
          font: "→"
        },
        {
          index: "2",
          font: "→"
        },
        {
          index: "3",
          font: "→"
        },
        {
          index: "4",
          font: "→"
        },
        {
          index: "5",
          font: "→"
        },
        {
          index: "6",
          font: "→"
        },
        {
          index: "7",
          font: "→"
        }
      ],
      RedKey: 1
    };
  },
  mounted: function() {

    let myPlayer = $("#videoShow")
    // myPlayer.on('play',() =>{
    // });
    myPlayer.on('pause',() =>{
      this.videoShow = true
      $('#videoShow')[0].pause()
    });
    $(".slick-area").slick({
      dots: true,
      infinite: false,
      speed: 400,
      slidesToShow: 6,
      slidesToScroll: 2,
      responsive: [
        {
          breakpoint: 1298,
          settings: {
            slidesToShow: 5,
            slidesToScroll: 2
          }
        },
        {
          breakpoint: 1024,
          settings: {
            slidesToShow: 4,
            slidesToScroll: 2
          }
        },
        {
          breakpoint: 768,
          settings: {
            slidesToShow: 3,
            slidesToScroll: 1
          }
        },
        {
          breakpoint: 600,
          settings: {
            slidesToShow: 2,
            slidesToScroll: 1
          }
        },
        {
          breakpoint: 480,
          settings: {
            slidesToShow: 1,
            slidesToScroll: 1
          }
        }
      ]
    });
  },
  methods: {
    noneCover: function() {
      this.videoShow = false
      $('#videoShow')[0].play()
    },
    closeX: function() {
      let pc = document.getElementById("BigHead-pc");
      pc.style.display = "none";
      let com = document.getElementById("BigHead-com");
      com.style.display = "none";
    },
    allShow: function() {
      (this.Solutions = [
        {
          image: require("../assets/log/icon_solution_client@2x.png"),
          Boldfont: "Client tamper-proof module",
          ComFont:
            "This module provides protection for specified directories for clients. Once the blockchain tamper proofing service starts to protect the specified client directory, any tampering operation (adding, deleting, modifying, moving the directory or file) to the directory, namely the subdirectories and files contained in the directory will be automatically restored. If the monitored protected directory is maliciously deleted, the client tamper-proof module will automatically identify the logged in system user and force the user to log off.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_user@2x.png"),
          Boldfont: "User management module",
          ComFont:
            "This module mainly provides for the specified ordinary user to add a protected directory on the target host, to allocate the existing protected directory, and to cancel the operation authorization of the specified user to the directory.Only after the ordinary user is authorized to specify the operation permission of the directory, can it carry on the resource management.The administrator has permission to operate on all directories on all target hosts. In addition, the module provides the ability to freeze and enable ordinary users.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_file@2x.png"),
          Boldfont: "File management module",
          ComFont:
            "This module provides resource management capabilities for protected directories on the specified target host.Users can add, delete, move, and rename files and directories, each of which generates a new version record, one of two ways to manage resources under the directory.In addition, the module provides the ability to pause and start protection for the specified root directory. Only after the protection is paused can the user make a manual resource change directly on the target host.When protection is enabled, changes are automatically identified and a new version is formed.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_version@2x.png"),
          Boldfont: "Version information maintenance module",
          ComFont:
            "This module provides version information maintenance function to protect directory, view all historical version information, and provide version recovery function. Each time the user changes the file through the 8-component blockchain tamper-proof service, suspends the root directory protection manual changes, and restarts the tamper-proof service, the corresponding version record will be generated.",
          show: false
        },
        {
          image: require("../assets/log/icon_solution_monitor@2x.png"),
          Boldfont: "Tamper-proof status monitoring module",
          ComFont:
            "This module provides tamper-proof service status on the target host, and users can see the running status of all tamper-proof services deployed with eight-component blockchain.Running states include normal and heart rate timeout.",
          show: false
        },
        {
          image: require("../assets/log/icon_solution_log@2x.png"),
          Boldfont: "User operation log module",
          ComFont:
            "This module provides the function of viewing the operation log of users through the tamper-proof service of our blockchain.It mainly contains the user's boot/pause root protection, new, delete, move and rename operation records.",
          show: false
        },
        {
          image: require("../assets/log/icon_solution_client log@2x.png"),
          Boldfont: "Client tamper-proof log module",
          ComFont:
            "This module provides the ability to record tampering actions against protected directories on the target host.Monitored tampering includes adding, deleting, modifying, and moving directories or files.",
          show: false
        }
      ]),
        (this.show = false);
    },
    allshrink() {
      this.Solutions = [
        {
          image: require("../assets/log/icon_solution_client@2x.png"),
          Boldfont: "Client tamper-proof module",
          ComFont:
            "This module provides protection for specified directories for clients. Once the blockchain tamper proofing service starts to protect the specified client directory, any tampering operation (adding, deleting, modifying, moving the directory or file) to the directory, namely the subdirectories and files contained in the directory will be automatically restored. If the monitored protected directory is maliciously deleted, the client tamper-proof module will automatically identify the logged in system user and force the user to log off.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_user@2x.png"),
          Boldfont: "User management module",
          ComFont:
            "This module mainly provides for the specified ordinary user to add a protected directory on the target host, to allocate the existing protected directory, and to cancel the operation authorization of the specified user to the directory.Only after the ordinary user is authorized to specify the operation permission of the directory, can it carry on the resource management.The administrator has permission to operate on all directories on all target hosts. In addition, the module provides the ability to freeze and enable ordinary users.",
          show: true
        },
        {
          image: require("../assets/log/icon_solution_file@2x.png"),
          Boldfont: "File management module",
          ComFont:
            "This module provides resource management capabilities for protected directories on the specified target host.Users can add, delete, move, and rename files and directories, each of which generates a new version record, one of two ways to manage resources under the directory.In addition, the module provides the ability to pause and start protection for the specified root directory. Only after the protection is paused can the user make a manual resource change directly on the target host.When protection is enabled, changes are automatically identified and a new version is formed.",
          show: true
        }
      ];
      this.show = true;
    },
    detail: function(num) {
      // console.log(num);
      let temp = {
        name: "",
        tit: "",
        pfonto: "",
        pfontt: "",
        pic: ""
      };
      if (num === "one") {
        (temp.pic = require("../assets/team/img_team_nizamoglu@2x.jpg")),
          (temp.name = "MEHMET NİZAMOĞLU"),
          (temp.tit = "Co-Founder & Chief Scientist"),
          (temp.pfonto =
            "Since graduating in Industrial engineering in 2001 from Middle East Technical University Mehmet Nizamoglu gained unparalleled experience focusing on IT applications in Turkey and in the US, working for major consulting firms such as BearingPoint (formerly KPMG), and SAP AG. In 2008 Mehmet returned to Turkey and worked as a lead architect at SAP AG Turkey. ");
        temp.pfontt =
          "He founded Voyacon Information Technologies in 2017, aiming to build state-of-the-art CRM solutions for commercial industries in the areas of Automotive Dealer Management System, Trade Promotion Optimization, and Loyalty solutions on cloud platform. He moved to blockchain space by leading the token model at an ICO project. His current interests are efficient Fundraising process, leading Token Economy sessions, and managing Investor Relations.";
      } else if (num === "two") {
        (temp.pic = require("../assets/team/img_team_leoChen@2x.png")),
          (temp.name = "Leo Chen"),
          (temp.tit = "Co-Founder & COO"),
          (temp.pfonto =
            "Leo Chen has got his Master Degree in Computer Security from Peking University. Before founding Authmen, he had worked for the CCID (China Center for Information Industry Development) for 7 years, and gained a deep understanding and connections in Chinese IT industry. Later he started Octa Innovations, China, a top cyber-security company in China building and providing leading products in operating system and cloud security built with Trusted Computing, Blockchain and Big Data technologies.");
        temp.pfontt =
          " He has also found the Octa-Peking University Joint Innovation Laboratory and served as the deputy manager. The joint laboratory has currently supported more than 4 professors and 22 PhD students in cyber security from Peking University, contributing more than 30 patents in crypto and blockchain related field.";
      } else if (num === "three") {
        (temp.pic = require("../assets/team/img_team_noPhoto@2x.jpg")),
          (temp.name = "Assoc. Prof. Mehmet Sabir Kiraz"),
          (temp.tit = "Co-Founder & Chief Scientist"),
          (temp.pfonto =
            "Mehmet Sabır Kiraz is currently working in De Montfort University, UK as an Assoc. Prof. He received his bachelor’s from Mathematics Department at Middle East Technical University in 2000. He worked at IT departments of Pamukbank and Yapi Kredi Bank as software engineer between June 2000 and September 2002. In October 2002, he started his M.Sc. studies (with full scholarship) at International Max Planck Research Institute for Computer Science, Germany and completed in November 2003. His thesis title is “Formalization and Verification of Informal Security Protocol Description”. He received his Ph.D. from Computer Science department at Eindhoven Technical University, the Netherlands in March 2008. His thesis title is “Secure and Fair Two-Party Computation”. He then worked at PHILIPS, Eindhoven and TOMTOM, Amsterdam as a test coordinator between 2008 and 2010. He worked as the director of Blockchain Research Lab at TUBITAK BILGEM Informatics and Information Security Research Center between Jan 2010 and Nov 2018. His current research interests include Cryptography, Cryptographic protocols, Privacy, PKI, Authentication and Key Management, Secure multiparty computation, Homomorphic encryption, Electronic voting, Cloud Security, Blockchain, and Cryptocurrencies.");
        temp.pfontt = " ";
      }
      this.data = temp;
      // console.log(this.data);
      let com = document.getElementById("BigHead-com");
      com.style.display = "block";
      let pc = document.getElementById("BigHead-pc");
      pc.style.display = "block";
    },
    slideLeft: function() {
      $("#roadmap").hide();
    },
    slideRight: function() {}
  }
};
</script>

<style lang="less" scoped>
@import "../../node_modules/slick-carousel/slick/slick.css";
@import "../../node_modules/slick-carousel/slick/slick-theme.css";
* {
  z-index: 10;
  // scrollbar-face-color:rgb(117, 121, 123);
  // scrollbar-arrow-color:rgb(95, 98, 101);
  // scrollbar-shadow-color:rgb(117, 121, 123);
  // scrollbar-track-color:rgb(25, 35, 39);
}
.noList li {
  padding-left: 0 !important;
  background: none !important;
}
.Vimg {
  display: none;
}
#BigHead-com {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  display: none;
  .ClickX {
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translate(-50%, 50%);
    width: 50px;
    height: 50px;
    // background:rgba(255,255,255,1);
    border: 1px solid rgba(240, 0, 0, 1);
    background-image: url("../assets/team/img_team_x@2x.jpg");
    background-size: 100% 100%;
    cursor: pointer;
  }
  .BigContainer {
    position: fixed;
    top: 100px;
    left: 50%;
    width: 424px;
    // height: 792px;
    height: auto;
    transform: translate(-50%, 0);
    background: rgba(255, 255, 255, 1);
    img {
      position: absolute;
      top: -20px;
      right: 0;
      width: 166px;
      height: 194px;
    }
    .LineFo {
      padding: 0 28px;
      box-sizing: border-box;
      margin-top: 202px;
      width: 311px;
      height: 20px;
      font-size: 16px;
      font-family: Lato;
      font-weight: bold;
      color: rgba(29, 29, 29, 1);
      line-height: 20px;
    }
    .LineFt {
      padding: 0 28px;
      box-sizing: border-box;
      width: 327px;
      background: rgba(240, 0, 0, 1);
      width: 311px;
      height: 30px;
      font-size: 14px;
      font-family: Lato;
      font-weight: 400;
      color: rgba(255, 255, 255, 1);
      line-height: 30px;
      margin: 8px 0 18px 0;
    }
    .LineFth {
      padding: 0 28px;
      box-sizing: border-box;
      // width: 368px;
      width: 100%;
      height: auto;
      font-size: 14px;
      font-family: Lato;
      font-weight: 400;
      color: rgba(80, 80, 80, 1);
      line-height: 22px;
      p {
        margin-bottom: 20px;
      }
    }
  }
}
#BigHead-pc {
  display: none;
  z-index: 15;
}
.RedBg {
  background: red;
  height: 100%;
}
#ShowDom {
  visibility: visible;
}
#ModelShow {
  display: block;
  p{
    font-size: 14px;
    font-family: Lato-Italic;
    font-weight: normal;
    color: #909090;
    line-height: 22px;
  }
}
.Shelter {
  position: absolute;
  background-image: url("../assets/bg/img_decoration_bg@2x.png");
  width: 100%;
  height: 3000px;
  top: 3200px;
  z-index: -1;
  background-size: 36px;
}
.tech-container {
  > div {
    position: relative;
    &:before {
      content: "";
      position: absolute;
      top: 103px;
      left: 0;
      right: 0;
      bottom: 64px;
      width: 100%;
      background: rgba(242, 242, 242, 1);
      background-image: url("../assets/bg/img_decoration_bg@2x.png");
      background-size: 36px;
    }
  }
  .techs {
    margin-top: -103px;
    .tech-details {
      padding: 64px 90px 46px;
      position: relative;
      background: url("../assets/bg/img_tech_bg.jpeg"),
        linear-gradient(
          226deg,
          rgba(229, 0, 0, 0.9) 0%,
          rgba(211, 0, 0, 1) 100%
        );
      background-size: cover;
      &:before {
        content: "";
        position: absolute;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        background: linear-gradient(
          226deg,
          rgba(229, 0, 0, 0.9) 0%,
          rgba(211, 0, 0, 1) 100%
        );
      }
      &:after {
        content: "";
        position: absolute;
        top: 0;
        right: 32px;
        width: 106px;
        height: 188px;
        background: url("../assets/bg/img_tech_plane@2x.png");
        background-size: contain;
      }
      h2 {
        position: relative;
        font-size: 20px;
        font-family: Lato-Black;
        font-weight: 900;
        color: rgba(255, 255, 255, 1);
        line-height: 24px;
        min-height: 24px;
        margin-bottom: 44px;
        &:before {
          display: block;
          content: "";
          border-width: 5px;
          border-style: solid;
          border-color: white white transparent transparent;
          transform: rotate(-90deg);
          /* 定位 */
          position: absolute;
          left: 42%;
          top: 34%;
        }
        &:after {
          display: block;
          content: "";
          border-width: 5px;
          border-style: solid;
          border-color: white white transparent transparent;
          transform: rotate(90deg);
          /* 定位 */
          position: absolute;
          left: -3%;
          top: 34%;
        }
      }
      > div {
        position: relative;
        p {
          float: left;
          font-size: 14px;
          font-family: Lato;
          font-weight: 400;
          color: rgba(255, 255, 255, 1);
          line-height: 20px;
          width: 45%;
        }
        .trust {
          font-size: 14px;
          font-family: Lato;
          font-weight: bold;
          color: rgba(255, 255, 255, 1);
          line-height: 22px;
          margin-bottom: 30px;
          margin-right: 40px;
        }
        .trust-mobile {
          display: none;
          // visibility:hidden;
        }
        .trust-left,
        .trust-right {
          width: 45%;
          height: auto;
          margin-bottom: 32px;
          display: inline-block;
          margin-right: 5%;
          .trust-child {
            width: 100%;
            font-size: 14px;
            font-family: Lato;
            color: rgba(255, 255, 255, 1);
            line-height: 28px;
            height: auto;
          }
        }
      }
    }
    .Techniques {
      // width: 844px;
      // height: 178px;
      width: auto;
      height: auto;
      background: rgba(255, 255, 255, 0.2);
      display: inline-block;
      // margin-top: 30px;
      display: flex;
      padding: 48px 78px;
      box-sizing: border-box;
      margin-left: -24px;
      div {
        flex: 1;
        ul {
          width: 100%;
          height: 100%;
          text-align: left;
          li {
            width: 100%;
            min-height: 22px;
            line-height: 22px;
            font-size: 14px;
            font-family: Lato-Bold;
            font-weight: 400;
            color: rgba(255, 255, 255, 1);
            list-style-type: none;
            background: url("../assets/misc/icon_bullet_transparent@2x.png")
              no-repeat 0px 3px;
            background-size: 9px 25px;
            padding-left: 18px;
            margin-bottom: 24px;
            background-position: left -2px;
          }
        }
      }
      div:nth-child(1) {
        // margin-right: 40px;
      }
      .Techniques-font {
        font-size: 20px;
        font-family: Lato;
        font-weight: normal;
        color: rgba(255, 255, 255, 1);
        line-height: 28px;
      }
    }
    .tech-features {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      margin-top: 36px;
      position: relative;
      > div {
        // width: 31.8%;
        width: 48.6%;
        height: 298px;
        // min-height: 158px;
        text-align: center;
        background: rgba(255, 255, 255, 1);
        border: 1px solid rgba(240, 0, 0, 1);
        margin-bottom: 18px;
        display: flex;
        flex-direction: row;
        div:nth-child(1) {
          width: 22%;
          height: 100%;
          position: relative;
          img {
            position: absolute;
            width: 50px;
            height: 50px;
            top: 20px;
            right: 20px;
          }
        }
        div:nth-child(2) {
          flex: 1;
          padding-top: 16px;
          padding-right: 24px;
          padding-bottom: 12px;
          box-sizing: border-box;
          text-align: left;
          h2 {
            font-size: 17px;
            font-family: Lato;
            font-weight: bolder;
            color: rgba(29, 29, 29, 1);
            line-height: 24px;
            margin-bottom: 6px;
          }
          p {
            overflow-x: hidden;
            overflow-y: scroll;
            height: 80%;
            font-size: 14px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(80, 80, 80, 1);
            line-height: 20px;
          }
          p::-webkit-scrollbar {
            height: 0;
            width: 0;
          }
          .InterlayerFont {
            width: 100%;
            height: 18px;
            font-size: 14px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(80, 80, 80, 1);
            line-height: 18px;
            margin-bottom: 20px;
          }
        }
      }
      > div:nth-child(3) {
        margin-bottom: 0;
      }
      > div:nth-child(4) {
        margin-bottom: 0;
      }
    }
  }
}
.works-container {
  width: 100%;
  height: auto;
  margin-top: 110px;
  text-align: center;
  background: white;
  position: relative;
  .works-bg {
    position: absolute;
    width: 100%;
    height: 222px;
    bottom: 0;
    left: 0;
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgBAMAAAAQtmoLAAAAAXNSR0IArs4c6QAAAA9QTFRF7+/v7u7u8PDw8vLy8fHxAhmJBwAAAK9JREFUeAHs1qERg1AQBuFNKoAOmNfC0gH995SJZhArEnUn/xOfXXi9vd+xPe7fx3V7rP1xh33d9tNje9jZIwFbI1iRwCMRYiQ4I4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEjglQhYkeDHpfGHmJleml6aXppeml6aXppeml76bGi3l0gfLQIAnAgVnjjUou0AAAAASUVORK5CYII);
    background-size: 36px;
    // background: red;
  }
  .line {
    width: 150px;
    height: 1px;
    background: #f00000;
    margin: 0 auto;
    margin-bottom: 46px;
  }
  .works-holder {
    font-family: Lato-Regular, Lato;
    font-size: 16px;
    padding-bottom: 68px;
    font-weight: 400;
    color: #1d1d1d;
    line-height: 24px;
  }
  .work-box {
    max-width: 1260px;
    padding: 0 16px;
    height: auto;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    .box-Differentiated {
      width: 100%;
      max-width: 1080px;
      height: 100%;
      background: white;
      padding-bottom: 112px;
      // padding: 0 220px;
      box-sizing: border-box;
      z-index: 10;
      display: flex;
      justify-content: center;
      position: relative;
      z-index: 1000;
      padding: 0 137px 112px 137px;
      .box-container {
        width: auto;
        height: auto;
        background: #ffffff;
        border-radius: 26px;
        border: 22px solid #fabebe;
        padding: 18px;
        display: flex;
        justify-content: center;
        position: relative;
        video {
          outline: none;
          max-height: 358px;
        }
        .video-cover{
          position: absolute;
          width:100%;
          height:100%;
          top:0;
          left:0;
          background-color: rgba(255,255,255,0.45);
          z-index: 1000;
        }
      }
    }
  }
}
.SolutionsContainer {
  background: white;
  width: 100%;
  height: auto;
  display: flex;
  justify-content: center;
  margin-top: 207px;
  position: relative;
  .SolutionsContainerCeng {
    width: 50%;
    height: 271px;
    position: absolute;
    top: 0;
    left: 0;
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgBAMAAAAQtmoLAAAAAXNSR0IArs4c6QAAAA9QTFRF7+/v7u7u8PDw8vLy8fHxAhmJBwAAAK9JREFUeAHs1qERg1AQBuFNKoAOmNfC0gH995SJZhArEnUn/xOfXXi9vd+xPe7fx3V7rP1xh33d9tNje9jZIwFbI1iRwCMRYiQ4I4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEjglQhYkeDHpfGHmJleml6aXppeml6aXppeml76bGi3l0gfLQIAnAgVnjjUou0AAAAASUVORK5CYII);
    background-size: 44px;
  }
  .Solution {
    width: 1080px;
    height: auto;
    .PaddingModel {
      position: relative;
      width: 50%;
      // width:33.333%;
      min-height: 271px;
      display: block;
      float: left;
      padding: 30px 0 30px 20px;
      box-sizing: border-box;
      background: white;
      border-bottom: 1px solid #dfdfdf;
      .HorizontalLine {
        width: 150px;
        height: 1px;
        background: rgba(240, 0, 0, 1);
      }
      .title-decorated {
        left: 0;
        position: absolute;
        top: 106px;
        font-size: 20px;
        b {
          font-size: 20px;
          font-family: Lato-Black, Lato;
          font-weight: 900;
          color: #1d1d1d;
          line-height: 30px;
          display: block;
        }
        span {
          margin-top: 10px;
          font-size: 14px;
          font-family: Lato-Regular, Lato;
          font-weight: 400;
          color: #1d1d1d;
          line-height: 22px;
        }
      }
      .Core {
        margin: 158px 0 102px 0;
      }
      img {
        width: 40px;
        height: 40px;
      }
      p {
        margin: 10px 0 0px 0;
        font-size: 12px;
        font-family: Lato;
        font-weight: 400;
        color: #505050;
        line-height: 18px;
      }
      .TitleFont {
        height: 22px;
        font-size: 16px;
        font-family: Lato;
        font-weight: bold;
        color: rgba(29, 29, 29, 1);
        line-height: 26px;
        margin-top: 28px;
      }
    }
    .PaddingModel:nth-child(1) {
      padding: 40px 0 32px 0;
    }
    .ModelEleven:nth-child(2n + 1) {
      padding-left: 0;
    }
    // .ModelEleven:nth-child(3n + 2) {
    //   padding: 40px 0 32px 13px;
    // }
    // .ModelEleven:nth-child(3n + 3) {
    //   padding-left: 28px;
    // }
    div:nth-child(1) {
      border: 0;
      background-color: rgba(46, 26, 26, 0);
    }
  }
}
.Usage {
  width: 100%;
  height: auto;
  // padding: 0 220px;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  .UsageContainer {
    width: 100%;
    max-width: 1080px;
    height: auto;
    display: flex;
    flex-direction: row;
    .ContainerLeft {
      width: 230px;
      height: 580px;
      background: rgba(29, 29, 29, 1);
      position: relative;
      ul {
        width: 100%;
        margin-bottom: 26px;
        height: auto;
        position: absolute;
        top: 0;
        margin-top: 88%;
        li {
          width: 100%;
          height: 54px;
          padding-right: 24px;
          box-sizing: border-box;
          text-align: right;
          font-size: 14px;
          font-family: Lato;
          font-weight: 400;
          color: rgba(255, 255, 255, 1);
          line-height: 54px;
        }
      }
    }
    .ContainerRight {
      flex: 1;
      background: rgba(255, 255, 255, 1);
      display: flex;
      .Hiddenarrow {
        width: 50px;
        height: auto;
        margin-right: 30px;
        position: relative;
        ul {
          position: absolute;
          bottom: 0;
          width: 100%;
          height: auto;
          li {
            width: 100%;
            height: 54px;
            visibility: hidden;
            background: red;
            padding: 12px;
            box-sizing: border-box;
            img {
              width: 100%;
              height: 100%;
            }
          }
        }
      }
      .ContentModel {
        flex: 1;
        padding: 72px 60px 72px 22px;
        box-sizing: border-box;
        > div {
          position: relative;
          display: none;
          .HorizontalLine {
            position: absolute;
            top: 0;
            left: 0;
            width: 197px;
            height: 2px;
            background: rgba(240, 0, 0, 1);
          }
          h3 {
            padding-top: 30px;
            font-size: 20px;
            font-family: Lato;
            font-weight: bold;
            color: rgba(29, 29, 29, 1);
            line-height: 28px;
            height: 28px;
          }
          span {
            font-size: 20px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(80, 80, 80, 1);
          }
        }
        .PkiImg {
          width: 100%;
          margin-top: 64px;
          height: 454px;
          img {
            width: 100%;
            height: 100%;
          }
        }
        .Fund {
          width: 100%;
          height: auto;
          display: flex;
          flex-direction: row;
          margin-top: 64px;
          ul {
            flex: 1;
            margin-right: 30px;
            li {
              margin: 18px 0;
              width: 100%;
              font-weight: 400;
              line-height: 22px;
              list-style-type: none;
              background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAAAXNSR0IArs4c6QAAALJJREFUeAGlkSEIwmAQRh8YbEarHTusJ3taT/a0ntaTPdmTvayD3WzbabAIc1/44RiOnecHjx13u8fBz1IMDoJ/MsDK4CpUk00Px5FBqM5eszG4F5Fq9TLXtBJMaPklL9jZ+JmK1NOMaAzOXuDRLCqpZiReVkVEXUDULUnqBYmX1XPPve7hFhXpX+18e+4mKPA0+DxhOzYtITLtUvKAkwYZtFuu2Ru8syLtyoHBJSspyPEBH2QrsEIhrTMAAAAASUVORK5CYII=)
                no-repeat 0px 8px;
              background-size: 10px 8px;
              padding-left: 18px;
              font-size: 14px;
              font-family: Lato-Regular;
              color: #505050;
              p {
                margin: 10px 0;
              }
            }
          }
          div {
            margin-left: 50px;
            flex: 1;
            img {
              width: 100%;
              height: 100%;
            }
          }
        }
        .Reviewing {
          width: 100%;
          height: 441px;
          display: flex;
          flex-direction: row;
          margin-top: 64px;
          div {
            flex: 1;
            margin-right: 30px;
            width: 100%;
            font-size: 16px;
            font-family: Lato;
            font-weight: bold;
            color: rgba(29, 29, 29, 1);
            line-height: 22px;
            p {
              width: 310px;
              font-size: 14px;
              font-family: Lato;
              font-weight: bold;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              margin-bottom: 30px;
            }
          }
          ul {
            width: 100%;
            li {
              margin-bottom: 18px;
              width: 100%;
              font-size: 14px;
              font-family: Lato;
              font-weight: 400;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              list-style-type: none;
              background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAAAXNSR0IArs4c6QAAALJJREFUeAGlkSEIwmAQRh8YbEarHTusJ3taT/a0ntaTPdmTvayD3WzbabAIc1/44RiOnecHjx13u8fBz1IMDoJ/MsDK4CpUk00Px5FBqM5eszG4F5Fq9TLXtBJMaPklL9jZ+JmK1NOMaAzOXuDRLCqpZiReVkVEXUDULUnqBYmX1XPPve7hFhXpX+18e+4mKPA0+DxhOzYtITLtUvKAkwYZtFuu2Ru8syLtyoHBJSspyPEBH2QrsEIhrTMAAAAASUVORK5CYII=)
                no-repeat 0px 8px;
              background-size: 10px 8px;
              padding-left: 14px;
              ul {
                li {
                  font-size: 13px;
                  margin: 8px 0;
                  list-style-type: none;
                  background: url("../assets/misc/icon_misc_bullet2@2x.png")
                    no-repeat 0px 8px;
                  background-size: 10px 8px;
                }
              }
            }
          }
        }
        .Crowd {
          width: 100%;
          height: 1000px;
          margin-top: 50px;
          display: flex;
          flex-direction: column;
          > div:nth-child(1) {
            flex: 3;
            display: flex;
            h3 {
              margin-bottom: 26px;
            }
            div {
              flex: 1;
              ul {
                width: 100%;
                li {
                  margin-bottom: 16px;
                  width: 100%;
                  font-size: 14px;
                  font-family: Lato;
                  font-weight: 400;
                  color: rgba(29, 29, 29, 1);
                  line-height: 22px;
                  list-style-type: none;
                  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAAAXNSR0IArs4c6QAAALJJREFUeAGlkSEIwmAQRh8YbEarHTusJ3taT/a0ntaTPdmTvayD3WzbabAIc1/44RiOnecHjx13u8fBz1IMDoJ/MsDK4CpUk00Px5FBqM5eszG4F5Fq9TLXtBJMaPklL9jZ+JmK1NOMaAzOXuDRLCqpZiReVkVEXUDULUnqBYmX1XPPve7hFhXpX+18e+4mKPA0+DxhOzYtITLtUvKAkwYZtFuu2Ru8syLtyoHBJSspyPEBH2QrsEIhrTMAAAAASUVORK5CYII=)
                    no-repeat 0px 8px;
                  background-size: 10px 8px;
                  padding-left: 14px;
                }
              }
            }
            div:nth-child(1) {
              margin-right: 40px;
            }
          }
          > div:nth-child(2) {
            width: 568px;
            height: 372px;
            margin-top: 32px;
            flex: 2;
            background-image: url("../assets/usage/img_us_cm.png");
            background-size: 100% 100%;
          }
        }
        .Coding {
          width: 100%;
          height: 1000px;
          display: flex;
          flex-direction: column;
          button {
            width: 100%;
            height: 30px;
            border: 0;
            font-size: 14px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(80, 80, 80, 1);
            line-height: 30px;
            outline: none;
            margin: 18px 0 42px 0;
          }
          .CodingFont {
            width: 100%;
            height: 148px;
            font-size: 14px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(29, 29, 29, 1);
            line-height: 22px;
            display: flex;
            margin: 64px 0 42px 0;
            div {
              flex: 1;
              margin-right: 30px;
              p {
                width: 326px;
                margin-bottom: 24px;
              }
            }
          }
          .CodingImgF {
            width: 100%;
            height: 100px;
            background-image: url("../assets/usage/img_us_signingCode.png");
            background-size: 100% 100%;
          }
          .CodingFlex {
            flex: 1;
            margin-bottom: 2px;
            background-image: url("../assets/usage/img_us_verfyingCode.png");
            background-size: 100% 100%;
          }
        }
        .Board {
          width: 100%;
          height: auto;
          margin-top: 64px;
          display: flex;
          > div {
            flex: 1;
            margin-right: 24px;
          }
          > div:nth-child(1) {
            display: flex;
            flex-direction: column;
            p {
              width: 100%;
              height: 44px;
              font-size: 14px;
              font-family: Lato;
              font-weight: 400;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
            }
            h2 {
              height: 22px;
              font-size: 18px;
              font-family: Lato;
              font-weight: bold;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              margin: 20px 0 30px 0;
            }
            ul {
              flex: 1;
              li {
                width: 318px;
                height: 110px;
                font-size: 14px;
                font-family: Lato;
                font-weight: 400;
                color: rgba(29, 29, 29, 1);
                line-height: 22px;
                list-style-type: none;
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAAAXNSR0IArs4c6QAAALJJREFUeAGlkSEIwmAQRh8YbEarHTusJ3taT/a0ntaTPdmTvayD3WzbabAIc1/44RiOnecHjx13u8fBz1IMDoJ/MsDK4CpUk00Px5FBqM5eszG4F5Fq9TLXtBJMaPklL9jZ+JmK1NOMaAzOXuDRLCqpZiReVkVEXUDULUnqBYmX1XPPve7hFhXpX+18e+4mKPA0+DxhOzYtITLtUvKAkwYZtFuu2Ru8syLtyoHBJSspyPEBH2QrsEIhrTMAAAAASUVORK5CYII=)
                  no-repeat 0px 8px;
                background-size: 10px 8px;
                padding-left: 14px;
              }
            }
          }
          > div:nth-child(2) {
            p {
              width: 300px;
              height: auto;
              font-size: 14px;
              font-family: Lato;
              font-weight: 400;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              margin-bottom: 22px;
            }
          }
        }
        .Information {
          width: 100%;
          height: 650px;
          margin-top: 64px;
          display: flex;
          > div {
            flex: 1;
            margin-right: 24px;
          }
          > div:nth-child(1) {
            div {
              width: 336px;
              height: 326px;
              background-image: url("../assets/usage/img_us_cw01.png");
              background-size: 100% 100%;
              margin-bottom: 30px;
            }
            h4 {
              width: 100%;
              height: 22px;
              font-size: 16px;
              font-family: Lato;
              font-weight: bold;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              margin: 36px 0 16px 0;
            }
            ul {
              li {
                width: 318px;
                height: 32px;
                font-size: 14px;
                font-family: Lato;
                font-weight: 400;
                color: rgba(29, 29, 29, 1);
                line-height: 32px;
                list-style-type: none;
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAAAXNSR0IArs4c6QAAALJJREFUeAGlkSEIwmAQRh8YbEarHTusJ3taT/a0ntaTPdmTvayD3WzbabAIc1/44RiOnecHjx13u8fBz1IMDoJ/MsDK4CpUk00Px5FBqM5eszG4F5Fq9TLXtBJMaPklL9jZ+JmK1NOMaAzOXuDRLCqpZiReVkVEXUDULUnqBYmX1XPPve7hFhXpX+18e+4mKPA0+DxhOzYtITLtUvKAkwYZtFuu2Ru8syLtyoHBJSspyPEBH2QrsEIhrTMAAAAASUVORK5CYII=)
                  no-repeat 0px 13px;
                background-size: 10px 8px;
                padding-left: 16px;
              }
            }
          }
          > div:nth-child(2) {
            div {
              width: 336px;
              height: 384px;
              background-image: url("../assets/usage/img_us_cw02.png");
              background-size: 100% 100%;
              margin-bottom: 30px;
            }
            h4 {
              width: 100%;
              height: 22px;
              font-size: 16px;
              font-family: Lato;
              font-weight: bold;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              margin: 36px 0 16px 0;
            }
            ul {
              li {
                width: 318px;
                height: 32px;
                font-size: 14px;
                font-family: Lato;
                font-weight: 400;
                color: rgba(29, 29, 29, 1);
                line-height: 32px;
                list-style-type: none;
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAAAXNSR0IArs4c6QAAALJJREFUeAGlkSEIwmAQRh8YbEarHTusJ3taT/a0ntaTPdmTvayD3WzbabAIc1/44RiOnecHjx13u8fBz1IMDoJ/MsDK4CpUk00Px5FBqM5eszG4F5Fq9TLXtBJMaPklL9jZ+JmK1NOMaAzOXuDRLCqpZiReVkVEXUDULUnqBYmX1XPPve7hFhXpX+18e+4mKPA0+DxhOzYtITLtUvKAkwYZtFuu2Ru8syLtyoHBJSspyPEBH2QrsEIhrTMAAAAASUVORK5CYII=)
                  no-repeat 0px 13px;
                background-size: 10px 8px;
                padding-left: 16px;
              }
            }
          }
        }
      }
    }
  }
}
.team-container {
  background: white;
  margin-top: 158px;
  position: relative;
  &::before {
    content: "";
    position: absolute;
    right: 0;
    top: 295px;
    width: 194px;
    height: 310px;
    background: url("../assets/bg/img_team_bg1@2x.png") no-repeat;
    background-size: 100% 100%;
    z-index: 1000;
  }
  &::after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    width: 156px;
    height: 316px;
    background: url("../assets/bg/img_team_bg2@2x.png") no-repeat;
    background-size: 100% 100%;
    z-index: 1000;
  }
  .center-area {
    padding-top: 112px;
    padding-bottom: 156px;
    text-align: center;
    min-height: 537px;
    box-sizing: border-box;
    .technology-box {
      padding-top: 110px;
      box-sizing: border-box;
      width: 100%;
      height: 411px;
      background: linear-gradient(
        180deg,
        rgba(255, 255, 255, 0) 0%,
        #ffffff 100%
      );
      background-image: url("../assets/bg/bg_technology@2x.png");
      background-size: 100% auto;
      h2 {
        font-size: 20px;
        font-family: Lato-Black, Lato;
        font-weight: 900;
        color: #1d1d1d;
        line-height: 24px;
        margin-bottom: 44px;
      }
      img {
        width: auto;
        height: 68px;
      }
    }
    .cover-bg {
      box-sizing: border-box;
      padding-top: 110px;
      max-width: 1080px;
      width: 100%;
      margin: 0 auto;
      height: 535px;
      background-image: url("../assets/bg/img_decoration_bg@2x.png");
      background-size: 44px;
    }
    .line {
      width: 150px;
      height: 1px;
      background: #f00000;
      margin: 0 auto;
      margin-bottom: 68px;
    }
    .title-decorated {
      margin-bottom: 38px;
      font-size: 20px;
      font-family: Lato-Black, Lato;
      font-weight: 900;
      color: #1d1d1d;
      line-height: 24px;
    }
    .Core {
      margin: 158px 0 102px 0;
    }
    .fluid-container {
      display: flex;
      // justify-content: space-around;
      flex-wrap: nowrap;
      .member {
        text-align: center;
        img {
          height: 194px;
          margin-bottom: 25px;
        }
        h3 {
          font-size: 16px;
          font-family: Lato;
          font-weight: bold;
          color: rgba(29, 29, 29, 1);
          line-height: 19px;
          margin-bottom: 10px;
        }
        p {
          font-size: 14px;
          font-family: Lato;
          font-weight: 400;
          color: rgba(80, 80, 80, 1);
          line-height: 20px;
          margin-bottom: 24px;
        }
        a {
          img {
            width: 24px;
            height: 24px;
          }
        }
        .AdFont {
          width: auto;
          max-width: 304px;
          height: 86px;
          font-size: 14px;
          font-family: Lato;
          font-weight: 400;
          color: rgba(80, 80, 80, 1);
          line-height: 22px;
        }
        button {
          margin-top: 6px;
          width: 136px;
          height: 36px;
          background: rgba(240, 0, 0, 1);
          border: 0;
          color: white;
          font-size: 14px;
          outline: none;
          cursor: pointer;
        }
      }
    }
    .partner-logo {
      width: 329px;
      height: 53px;
    }
  }
  .area {
    max-width: 100%;
    padding: 0;
    // padding-bottom: 156px;
  }
}
.Footer {
  .pc {
    display: none;
  }
  width: 100%;
  height: auto;
  padding: 94px 72px 0 72px;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  .footer-main {
    width: 1296px;
    height: auto;
    .Gray-line {
      width: 100%;
      height: 1px;
      background: rgba(216, 216, 216, 1);
      margin-bottom: 12px;
    }
    .Authmen {
      text-align: center;
      width: 100%;
      height: 20px;
      font-size: 14px;
      font-family: Lato;
      font-weight: 400;
      color: rgba(124, 124, 124, 1);
      line-height: 20px;
      margin-bottom: 38px;
    }
    > div:nth-child(1) {
      width: 100%;
      height: 40px;
      line-height: 40px;
      div {
        float: left;
        width: 146px;
        height: 100%;
        background-image: url("../assets/New Folder With Items/red.png");
        background-repeat: no-repeat;
        background-position: top left;
        background-size: 143px 40px;
      }
      ul {
        float: right;
        li {
          float: left;
          width: 61px;
          text-align: center;
          height: 24px;
          font-size: 13px;
          font-family: Lato;
          font-weight: 400;
          color: rgba(29, 29, 29, 1);
          line-height: 24px;
          margin-right: 32px;
          a{
            text-decoration: none;
            color: rgba(29, 29, 29, 1);
          }
        }
        li:last-child {
          margin: 0;
        }
      }
    }
    > div:nth-child(2) {
      margin: 24px 0 32px 0;
      width: 346px;
      height: 40px;
      font-size: 14px;
      font-family: Lato;
      font-weight: 400;
      color: rgba(29, 29, 29, 1);
      line-height: 20px;
    }
    > div:nth-child(3) {
      width: 100%;
      height: 40px;
      margin-bottom: 48px;
      ul {
        width: 100%;
        height: 100%;
        li {
          float: left;
          width: 40px;
          height: 40px;
          margin-right: 16px;
          a {
            width: 100%;
            height: 100%;
            img {
              width: 100%;
              height: 100%;
            }
          }
        }
      }
    }
  }
}

@roadmap-item-width: 158px;
@roadmap-item-height: 340px;
@roadmap-item-line-height: 4px;
@roadmap-item-line-margin: 4px;
@roadmap-timepoint-width: 12px;
@roadmap-item-left-line-width: calc(
  ~"50% - @{roadmap-item-line-margin} - @{roadmap-timepoint-width}/2 - 70px"
);
@roadmap-item-right-line-width: calc(
  ~"50% - @{roadmap-item-line-margin} - @{roadmap-timepoint-width}/2 + 70px"
);
.roadmap-container {
  height: 630px;
  background: url("../assets/bg/img_roadmap_bg.jpeg") #3b3b3b;
  background-size: cover;
  background-blend-mode: multiply;
  text-align: center;
  .title {
    display: inline-block;
    width: 456px;
    height: 85px;
    position: relative;
    background: #1c0000;
    > div {
      position: absolute;
      left: 0;
      right: 0;
      top: -125px;
      bottom: 0;
      height: 210px;
    }
    .bg {
      background: rgba(222, 0, 0, 1);
      mix-blend-mode: multiply;
    }
    h2 {
      font-size: 20px;
      font-weight: 900;
      color: rgba(255, 255, 255, 1);
      line-height: 24px;
      margin-top: 40px;
      margin-bottom: 5px;
      z-index: 1;
      font-family: Lato-Black, Lato;
    }
    p {
      font-size: 14px;
      font-family: Lato-Regular, Lato;
      font-weight: 400;
      color: #ffffff;
      line-height: 24px;
    }
  }
  .roadmap-slick {
    margin-top: 87px;
    width: 90%;
    display: inline-block;
    :focus {
      outline: none;
    }
    .slick-area {
      div {
        user-select: none;
      }
      .slick-item {
        position: relative;
        width: @roadmap-item-width;
        height: @roadmap-item-height;
        display: inline-block;
        .baseline {
          position: relative;
          margin-top: (@roadmap-item-height - @roadmap-timepoint-width)/2 - 4px;
          .left-line,
          .right-line {
            width: @roadmap-item-left-line-width;
            height: @roadmap-item-line-height;
            background: #3b3b3b;
            display: inline-block;
            vertical-align: middle;
          }
          .right-line {
            margin-left: @roadmap-item-line-margin;
            width: @roadmap-item-right-line-width;
          }
          .point {
            display: inline-block;
            position: relative;
            box-sizing: border-box;
            width: @roadmap-timepoint-width;
            height: @roadmap-timepoint-width;
            background: rgba(20, 23, 26, 1);
            border: 3px solid #f00000;
            margin-left: @roadmap-item-line-margin;
            vertical-align: middle;
          }
          .rm-info {
            position: absolute;
            left: 2.5px;
            bottom: 13px;
            // width: 211px;
            width: 340px;
            font-size: 14px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(255, 255, 255, 1);
            line-height: 24px;
            border-left: 1px solid #e5e5e5;
            padding-left: 10px;
            padding-bottom: 55px;
            text-align: left;
            &.top {
              padding: 0 0 61px 8px;
              border-left: 1px solid #e5e5e5;
            }
            &.top {
              padding: 61px 0 0 8px;
              border-left: 1px solid #e5e5e5;
            }
          }
          .rm-date {
            position: absolute;
            width: 130px;
            height: 24px;
            font-size: 14px;
            font-family: Lato;
            font-weight: 900;
            color: rgba(208, 208, 208, 1);
            line-height: 24px;
            bottom: auto;
            top: 13px;
            left: -26px;
          }
        }
        .baseline.up {
          .rm-info {
            top: 13px;
            bottom: auto;
            padding-bottom: 0;
            padding-top: 55px;
          }
          .rm-date {
            top: auto;
            bottom: 13px;
          }
        }
      }
    }
  }
}
@media screen and (max-width: 768px) {
  .Vimg {
    display: block;
  }
  .Eliminaterolling::-webkit-scrollbar {
    width: 0 !important;
  }
  #app {
    overflow-x: hidden;
  }
  .title-decorated {
    text-align: left;
  }
  .title-web {
    position: relative;
    &:after {
      display: block;
      content: "";
      border-width: 6px;
      border-style: solid;
      border-color: red red transparent transparent;
      transform: rotate(-270deg);
      /* 定位 */
      position: absolute;
      left: 22%;
      bottom: 18%;
    }
    &:before {
      display: block;
      content: "";
      border-width: 6px;
      border-style: solid;
      border-color: red red transparent transparent;
      transform: rotate(270deg);
      /* 定位 */
      position: absolute;
      right: 22%;
      top: 18%;
    }
  }
  .tech-container .techs .tech-details h2::before {
    border-width: 0 !important;
  }
  .tech-container .techs .tech-details h2::after {
    border-width: 0 !important;
  }
  .SolutionsContainerCeng {
    display: none;
  }
  .Shelter {
    top: 3025px;
    height: 300px;
  }
  .Usage {
    padding: 0;
    .UsageContainer {
      width: 100%;
      flex-direction: column;
      .ContainerLeft {
        width: 100%;
        height: 72px;
        position: relative;
        z-index: 1000;
        ul {
          padding: 0 16px;
          box-sizing: border-box;
          overflow-x: auto;
          overflow-y: hidden;
          width: 100%;
          height: 100px;
          margin: 0;
          display: flex;
          li {
            padding-right: 0;
            text-align: center;
            min-width: 151px;
            height: 90px;
            line-height: 90px;
            float: left;
          }
          .RedBg {
            position: relative;
            .line {
              position: absolute;
              width: 40px;
              height: 1px;
              bottom: 18px;
              left: 50%;
              transform: translateX(-50%);
              background: #ffffff;
            }
          }
        }
      }
      .ContainerRight {
        flex-direction: column;
        position: relative;
        z-index: 10;
        .Hiddenarrow {
          display: none;
        }
        .ContentModel {
          padding: 48px 16px 88px 16px;
          background-size: 36px;
          background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgBAMAAAAQtmoLAAAAAXNSR0IArs4c6QAAAA9QTFRF7+/v7u7u8PDw8vLy8fHxAhmJBwAAAK9JREFUeAHs1qERg1AQBuFNKoAOmNfC0gH995SJZhArEnUn/xOfXXi9vd+xPe7fx3V7rP1xh33d9tNje9jZIwFbI1iRwCMRYiQ4I4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEjglQhYkeDHpfGHmJleml6aXppeml6aXppeml76bGi3l0gfLQIAnAgVnjjUou0AAAAASUVORK5CYII=);
          #ModelShow {
            h3 {
              b {
                display: block;
                margin-bottom: 12px;
              }
            }
            .Fund {
              height: auto;
              background: white;
              padding: 36px 16px;
              box-sizing: border-box;
              flex-direction: column;
              margin-top: 112px;
              div {
                margin: 0;
              }
            }
            .Reviewing {
              background: white;
              flex-direction: column;
              padding: 36px 16px;
              box-sizing: border-box;
              height: auto;
              ul {
                li {
                  ul {
                    li {
                      font-size: 12px;
                    }
                  }
                }
              }
            }
            .Crowd {
              background: white;
              flex-direction: column;
              padding: 36px 16px;
              box-sizing: border-box;
              height: auto;
              margin-top: 136px;
              > div {
                flex-direction: column;
              }
            }
          }
          .Fund ul{
            margin-right: 16px;
          }
          .Fund ul li{
            margin:14px 0;
            font-family: inherit;
          }
          .PkiImg {
            padding: 36px 16px;
            box-sizing: border-box;
            background: rgba(255, 255, 255, 1);
            margin-top: 100px;
          }
          .Coding {
            padding: 36px 16px;
            box-sizing: border-box;
            background: rgba(255, 255, 255, 1);
            margin-bottom: 100px;
          }
          .Board {
            padding: 36px 16px;
            box-sizing: border-box;
            background: rgba(255, 255, 255, 1);
            margin-top: 100px;
            flex-direction: column;
            > div:nth-child(1) {
              margin-bottom: 44px;
              h2 {
                margin: 40px 0 10px 0;
              }
            }
          }
          .Information {
            height: auto;
            padding: 36px 0px;
            box-sizing: border-box;
            background: rgba(255, 255, 255, 1);
            margin-top: 100px;
            flex-direction: column;
            // h4{
            //   padding:0 16px;
            //   box-sizing:border-box;
            // }
            div {
              margin: 0 auto;
            }
          }
        }
      }
    }
  }
  .SolutionsContainer {
    margin-top: 80px;
    .Solution {
      width: 100%;
      height: auto;
      position: relative;
      padding-bottom: 150px;
      div:nth-child(1) {
        padding: 0 !important;
        background-size: 36px;
        background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgBAMAAAAQtmoLAAAAAXNSR0IArs4c6QAAAA9QTFRF7+/v7u7u8PDw8vLy8fHxAhmJBwAAAK9JREFUeAHs1qERg1AQBuFNKoAOmNfC0gH995SJZhArEnUn/xOfXXi9vd+xPe7fx3V7rP1xh33d9tNje9jZIwFbI1iRwCMRYiQ4I4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEhgJDASGAmMBEYCI4GRwEjglQhYkeDHpfGHmJleml6aXppeml6aXppeml76bGi3l0gfLQIAnAgVnjjUou0AAAAASUVORK5CYII=);
      }
      .PaddingModel {
        width: 100%;
        padding: 54px 0 30px 0;
        .title-decorated {
          left: 0;
          top: 41px;
          padding: 0 16px;
          box-sizing: border-box;
        }
        .HorizontalLine {
          margin: 0 auto;
          // margin-top: 16px;
        }
      }
      .PaddingModel:nth-child(1) {
        min-height: 154px;
      }
      .ModelEleven:nth-child(3n + 1) {
        padding: 42px 16px 24px 16px;
      }
      .ModelEleven:nth-child(3n + 2) {
        padding: 42px 16px 24px 16px;
      }
      .ModelEleven:nth-child(3n + 3) {
        padding: 42px 16px 24px 16px;
      }
      .FuzzyGradualChange {
        width: 100%;
        height: 229px;
        background: rgba(255, 255, 255, 0.6);
        position: absolute;
        bottom: 0;
        .Vimg {
          display: block;
          text-align: center;
          width: 343px;
          height: 42px;
          background: rgba(255, 255, 255, 1);
          border: 1px solid rgba(240, 0, 0, 1);
          font-size: 16px;
          font-family: Lato;
          font-weight: bold;
          color: rgba(240, 0, 0, 1);
          line-height: 42px;
          letter-spacing: 2px;
          margin: 0 auto;
          margin-top: 100px;
        }
      }
    }
  }
  .works-container {
    margin-top: 128px;
    .works-bg {
      height: 300px;
      bottom: -140px;
    }
    .work-box {
      position: relative;
      z-index: 10000;
      .WhiteShelter {
        display: none;
      }
      .box-Differentiated {
        padding: 0 16px 32px 16px;
        // padding-bottom: 32px;
        .box-container {
          background-repeat: no-repeat;
          background-size: 96% 100%;
          background-position: 50% 0;
          padding: 8px;
          box-sizing: border-box;
          width: 343px;
          height: auto;
          position: relative;
          border-radius: 8px;
          border: 8px solid #fabebe;
          video {
            width: 100%;
            min-height: auto;
          }
        }
      }
      .Vimg {
        position: absolute;
        bottom: -84px;
        width: 311px;
        height: 42px;
        background: rgba(255, 255, 255, 1);
        border: 1px solid rgba(240, 0, 0, 1);
        font-size: 16px;
        font-family: Lato;
        font-weight: bold;
        color: rgba(240, 0, 0, 1);
        line-height: 42px;
        letter-spacing: 2px;
      }
    }
    .works-holder {
      padding-bottom: 48px;
    }
  }
  .title-decorated {
    text-align: center;
    margin-bottom: 30px;
  }
  .tech-container {
    > div::before {
      bottom: 120px;
    }
    .techs {
      margin-top: -86px;
      padding: 0;
      .tech-features {
        // overflow-x: auto;
        // white-space: nowrap;
        // display: -webkit-box;
        overflow-y: hidden;
        overflow-x: scroll;
        position: relative;
        width: 100vw;
        display: flex;
        flex-wrap: inherit;
        > div {
          text-align: left;
          width: 244px;
          height: 238px;
          margin-right: 16px;
          flex-direction: column;
          padding: 0 0 0 18px;
          box-sizing: border-box;
          div:nth-child(1) {
            width: 100%;
            height: 22%;
            img {
              left: 0;
              position: relative;
            }
          }
          div:nth-child(2) {
            .InterlayerFont {
              // margin-bottom: 8px;
              display: none;
            }
            p {
              white-space: normal;
              width: 208px;
              height: 80px;
              font-size: 14px;
              font-family: Lato;
              font-weight: 400;
              color: #505050;
              line-height: 20px;
            }
            h2 {
              margin-top: 20px;
            }
          }
        }
      }
      .Techniques {
        width: 100%;
        margin: 0 auto;
        height: auto;
        // height: 345px;
        flex-direction: column;
        padding: 48px 16px;
        // padding-bottom:26px;
        .Techniques-font {
          text-align: center;
          margin: 21px 0 26px 0;
        }
        li {
          box-sizing: border-box;
          margin-bottom: 16px !important;
          font-family: Lato-Bold, Lato !important;
          font-weight: bold;
          color: #ffffff;
          line-height: 22px;
        }
        li:last-child {
          margin-bottom: 0 !important;
        }
      }
      .tech-details {
        padding: 46px 16px 50px 16px;
        h2 {
          margin: 0;
          font-size: 20px;
          font-family: Lato-Black, Lato;
          font-weight: 900;
          color: #ffffff;
          line-height: 28px;
          margin-bottom: 48px;
          text-align: left;
        }
        > div {
          .trust:nth-child(2) {
            display: none;
          }
          .trust-mobile {
            display: block;
          }
          .trust {
            margin: 32px 0 16px 0;
          }
          .trust-left {
            width: 100%;
            height: auto;
            margin: 0;
            .trust-child {
              margin: 0;
            }
          }
          .trust-right {
            width: 100%;
            height: auto;
            margin: 0;
            .trust-child {
              margin: 0;
            }
          }
          p {
            float: none;
            width: 100%;
            &:nth-child(2) {
              margin-top: 40px;
            }
            &:last-child {
              margin-top: 40px;
            }
          }
        }
        &:after {
          display: none;
        }
      }
    }
  }
  .team-container::after {
    width: 76px;
    height: 154px;
  }
  .team-container::before {
    width: 76px;
    height: 121px;
    top: 272px;
  }
  .team-container {
    margin-top: 0;
    &:before {
      top: 354px;
    }
    .center-area {
      min-height: auto;
      // padding-bottom: 240px;
      .line {
        margin-bottom: 46px;
      }
      .Core {
        margin: 0 0 72px 0;
      }
      .AdFont {
        width: 220px;
        min-height: 132px;
        height: auto !important;
      }
      .cover-bg {
        width: 92%;
        padding-top: 96px;
      }
    }
    .fluid-container {
      display: block;
      padding: 0 16px;
      box-sizing: border-box;
      overflow-x: auto;
      width: 100%;
      height: auto;
      margin: 0;
      display: flex;
      justify-content: left;
      .member {
        width: 230px;
        min-height: 450px;
        float: left;
        margin-right: 42px;
        h3 {
          width: 230px;
        }
        .AdFont {
          max-width: 220px;
        }
      }
    }
  }
  .roadmap-container {
    .title {
      width: 80%;
      height: 60px;
      h2 {
        margin-top: 31px;
      }
      div {
        top: -110px;
        height: 170px;
      }
    }
  }
  .Footer {
    .footer-main {
      > div:nth-child(1) {
        ul {
          display: none;
        }
      }
      .Authmen {
        height: auto;
        text-align: left;
      }
    }
    .pc {
      display: block;
      height: auto;
      li {
        font-weight: bold;
        width: auto;
        margin-bottom: 32px;
        height: 24px;
        font-size: 15px;
        font-family: Lato;
        color: rgba(29, 29, 29, 1);
        line-height: 24px;
      }
      li:last-child {
        margin-bottom: 54px;
      }
    }
  }
  #BigHead-com {
    display: none;
  }
  #BigHead-pc {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    display: none;
    .ClickX {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translate(-50%, 50%);
      width: 50px;
      height: 50px;
      // background:rgba(255,255,255,1);
      border: 1px solid rgba(240, 0, 0, 1);
      background-image: url("../assets/team/img_team_x@2x.jpg");
      background-size: 100% 100%;
    }
    .BigContainer {
      position: fixed;
      top: 50px;
      left: 16px;
      width: 343px;
      height: 720px;
      background: rgba(255, 255, 255, 1);
      img {
        position: absolute;
        top: -20px;
        right: 16px;
        width: 166px;
        height: 194px;
      }
      .LineFo {
        padding: 0 16px;
        box-sizing: border-box;
        margin-top: 202px;
        width: 311px;
        height: 20px;
        font-size: 16px;
        font-family: Lato;
        font-weight: bold;
        color: rgba(29, 29, 29, 1);
        line-height: 20px;
      }
      .LineFt {
        padding: 0 16px;
        box-sizing: border-box;
        width: 327px;
        background: rgba(240, 0, 0, 1);
        width: 311px;
        height: 30px;
        font-size: 14px;
        font-family: Lato;
        font-weight: 400;
        color: rgba(255, 255, 255, 1);
        line-height: 30px;
        margin: 8px 0 18px 0;
      }
      .LineFth {
        padding: 0 16px;
        box-sizing: border-box;
        width: 340px;
        height: 412px;
        font-size: 14px;
        font-family: Lato;
        font-weight: 400;
        color: rgba(80, 80, 80, 1);
        line-height: 22px;
        p {
          margin-bottom: 20px;
        }
      }
    }
  }
}
</style>
