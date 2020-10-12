<template>
  <div class="tabs-container">
    <div class="tab-content">
      <div class="center-area">
        <div class="active">
          <div class="line" />
          <h2>A Trusted Blockchain Storage Protocol</h2>
          <!-- <h4>Decentralized Web: Decentralized Anonymous Board of Experts</h4> -->
          <div class="fluid-container">
            <div>
              <h3>What is Authmen?</h3>
              <ul>
                <li>
                  Authmen is a trusted blockchain storage protocol. It is a new
                  storage scheme based on the distributed idea of blockchain. It
                  mainly solves the problems of data storage and data flow.
                  Using trusted blockchain technology distributed high
                  availability, open and transparent, tamper proof, information
                  security and other technical characteristics, to build
                  information security tamper proof and traceability system.
                </li>
              </ul>
              <h3>What’s your big vision?</h3>
              <ul>
                <li>
                  Powered by Authmen, your storage process will be more
                  trustful, efficient,reliable, temper-proof, permanent,
                  retrieved quickly, and decentralized.
                </li>
                <li>
                  Enjoy more secure and privacy enhanced Authmen storage network
                  for free through defi based token economics.
                </li>
              </ul>
            </div>
            <div>
              <h3>What’s the core problem we are solving?</h3>
              <ul>
                <li>
                  At present, the pain point of Internet storage and the rigid
                  demand of sortage market is one of the urgent problems to be
                  solved in blockchain. However, the distributed storage of
                  hundreds of trillions of data on the blockchain is obviously
                  still in an untrustworthy environment. In the track of
                  decentralized storage, the core problem to be solved is the
                  proof of data integrity,so that the following pain points need
                  to be solved:
                  <p>
                    1. How to prove the authenticity of user data stored by
                    miners?
                  </p>
                  <p>
                    2. How to prove that the miner kept the data as promised?
                  </p>
                  <p>
                    3. How to avoid false data storage? Inject junk data to
                    defraud additional issuance rewards?
                  </p>
                </li>
                <!-- <li></li> -->
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- <ul class="center-area">
      <li
        v-for="tab in tabs"
        v-bind:key="tab.key"
        v-bind:class="['tab-button', { active: currentTabKey === tab.key }]"
        v-on:click="currentTabKey = tab.key"
      >
        <img
          v-bind:src="currentTabKey === tab.key ? tab.activeIcon : tab.icon"
          alt=""
        />{{ tab.text }}
      </li>
    </ul>
    <div class="tab-content">
      <div class="center-area">
        <div v-bind:class="{ active: currentTabKey === 1 }">
          <h2>Authmen: Decentralized Anonymous Board of Experts</h2>
          <div class="fluid-container">
            <div>
              <p class="tab-font">What’s the solution?</p>
              <p>
                Usage of certificates has not been expanded to many other
                potential areas due to monopoly of CAs.
              </p>
              <p class="tab-font">What’s your big vision?</p>
              <p>
                Leverage consensus-based participatory democracy in internet
                society.
              </p>
            </div>
            <div>
              <ul>
                <p class="tab-font">What’s the core problem we are solving?</p>
                <li>
                  Certificate Authorities (CAs) are assumed to be ultimately
                  trusted organizations
                </li>
                <li>
                  Individuals are not part of decision making process due to
                  privacy issues.
                </li>
                <li>
                  Issues around Identity & Attribute Management of individuals.
                </li>
                <li>Transparency vs anonymity .</li>
              </ul>
            </div>
          </div>
        </div>
        <div v-bind:class="{ active: currentTabKey === 2 }">
          <h2>What if CAs are Corrupted?</h2>
          <div class="fluid-container">
            <div>
              <h3>Identity Documents in the Real World</h3>
              <h3>
                What is an identity document? (Passport, birth certificate,
                driver’s license)
              </h3>
              <ul>
                <li>
                  A piece of paper.
                </li>
                <li>
                  Issued by a Trusted Third Party (Government Agencies).
                </li>
                <li>
                  With information verifying the identity of the holder.
                </li>
              </ul>
              <h3>
                An identity document is useless unless the holder can be
                challenged to demonstrate that he is the person named in the
                document.
              </h3>
              <ul>
                <li>
                  Photograph
                </li>
                <li>
                  Signature
                </li>
                <li>
                  Fingerprint
                </li>
              </ul>
            </div>

            <div>
              <h3>Digital Certificates in the Cyber Space</h3>
              <ul>
                <li>
                  A digital identity document binding a public-private key pair
                  to a specific person or organization.
                </li>
                <li>
                  Verifying a digital signature only proves that the signer had
                  the private key corresponding to the public key used to
                  decrypt the signature.
                </li>
                <li>
                  Does not prove that the public-private key pair belonged to
                  the claimed individual.
                </li>
                <li>
                  We need an independent third party to verify the person’s
                  identity (through non-electronic means) and issue a digital
                  certificate.
                </li>
              </ul>
              <h4>Name of holder</h4>
              <p>Digital Signature of CA</p>
              <h4>Public key of holder</h4>
              <p>Data on which hash and public-key algorithms have been used</p>
              <h4>Name of trusted third party (Certificate Authority (CA))</h4>
              <p>Other business or personal information</p>
            </div>
          </div>
        </div>
        <div v-bind:class="{ active: currentTabKey === 3 }">
          <h2>Recent Incidents</h2>
          <div class="fluid-container">
            <div>
              <h3>Comodo CA, March 2011</h3>
              <ul>
                <li>
                  Attacked RA, 9 fraudulent certificates to mail.google.com,
                  login.skype.com, login.live.com etc.
                </li>
              </ul>
              <h3>Dutch CA DigiNotar, July 2011,</h3>
              <ul>
                <li>
                  531 fraudulent certificates to *.google.com,
                  *.windowsupdate.com, *.mozilla.com etc. Iranian government
                  used them to spy on citizens.
                </li>
              </ul>
              <h3>2 Taiwanese CAs compromised, 2011,</h3>
              <ul>
                <li>
                  To sign Stuxnet Malware
                </li>
              </ul>
            </div>
            <div>
              <h3>Turkish CA TurkTrust, Dec 2012.</h3>
              <ul>
                <li>
                  Mistakenly issued a subCA certificate as a TLS certificate.
                  Used for MITM traffic inspection.
                </li>
              </ul>
              <h3>Lenovo Superfish, 2015,</h3>
              <ul>
                <li>
                  Deployed local CA in notebooks to inject ads to TLS protected
                  sites.
                </li>
              </ul>
              <h3>Symantec, 2015,</h3>
              <ul>
                <li>
                  Mis-issued certificates for Opera.
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div v-bind:class="{ active: currentTabKey === 4 }">
          <h2>Problem of Current Market</h2>
          <div class="fluid-container">
            <div>
              <p>
                Usage of certificates has not been expanded to many other
                potential areas due to monopoly of CAs.
              </p>
              <p class="RedFont">Can we move this to decentralized world?</p>
            </div>
            <div>
              <ul>
                <li>
                  <b class="BoldBlackFont">Problem 1: </b>A Certificate
                  Authority is often defined as "trusted" entity. However,
                  reality falls far short of this trust relationship according
                  to various incidents.
                </li>
                <li>
                  <b class="BoldBlackFont">Problem 2: </b>People are forced to
                  make a choice between sacrificing privacy to take part in the
                  digital world and sacrificing participation in modern society
                  to protect privacy.
                </li>
                <li>
                  <b class="BoldBlackFont">Problem 3: </b>Deliberately
                  misleading or biased information is considered to be major
                  problem in internet society. Lack of reliability of sources of
                  Information.
                </li>
                <li>
                  <b class="BoldBlackFont">Problem 4: </b>People should have
                  right to stay anonymous. Data provided over internet should
                  not be traced back to compromise privacy of individuals.
                </li>
                <li>
                  <b class="BoldBlackFont">Problem 5: </b>Lack of secure
                  platforms for individuals or group of people (experts) to
                  participate in decision making without revealing their
                  identity
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div v-bind:class="{ active: currentTabKey === 5 }">
          <h2>Why Authmen?</h2>
          <div class="fluid-container">
            <div>
              <h3>
                Anonymity: Hiding link between identity and action/piece of
                information.
              </h3>
              <ul>
                <li>Reader of a web page, person accessing a service.</li>
                <li>
                  Sender of an email, writer of a text.
                </li>
                <li>
                  Person present in a physical location.
                </li>
              </ul>
              <h3>Right to privacy</h3>
              <ul>
                <li>
                  Companies, governments and other entities may try to track
                  users in the Internet.
                </li>
                <li>
                  Possibility to link the users’ actions.
                </li>
                <li>
                  Possibility to track users without their knowledge or consent.
                </li>
              </ul>
              <h3>Freedom of Speech</h3>
              <h3>
                Unlinkability: Hiding link between two or more actions /
                identities / info pieces.
              </h3>
              <ul>
                <li>Two anonymous letters written by the same person.</li>
                <li>Two web page visits by the same user.</li>
                <li>Two people related by a friendship link.</li>
                <li>
                  Same person spotted in two locations at different points in
                  time.
                </li>
              </ul>
            </div>
            <div>
              <h3>
                Unobservability: Hiding user activity.
              </h3>
              <ul>
                <li>
                  whether someone is accessing a web page.
                </li>
                <li>
                  whether an entry in a database corresponds to a real person.
                </li>
                <li>
                  whether someone or no one is in a given location.
                </li>
              </ul>
              <h3>
                Plausible deniability: Not possible to prove user knows, has
                done or has said something.
              </h3>
              <ul>
                <li>
                  Off-the-record conversations.
                </li>
                <li>
                  Resistance to coercion: Not possible to prove that a person
                  has hidden information in a computer. Not possible to know
                  that someone has the combination of a safe
                </li>
                <li>
                  Possibility to deny having been in a place at a certain point
                  in time.
                </li>
                <li>
                  Possibility to deny that a database record belongs to a
                  person.
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div v-bind:class="{ active: currentTabKey === 6 }">
          <h2>CertLedger Revenue Stream</h2>
          <div class="fluid-container center">
            <div class="CenterBox">
              <div class="CenterBoxTop">
                <div>Digital Credentials in current PKI</div>
                <div>Anonymous Credentials</div>
              </div>
              <div class="CenterBoxMain">
                <ul>
                  <li>
                    Signed by a trusted issuer
                  </li>
                  <li>
                    Certification of attributes.
                  </li>
                  <li>
                    Authentication (secret key).
                  </li>
                  <li>
                    Double-signing detection.
                  </li>
                </ul>
              </div>
              <div class="CenterBoxBottom">
                <div>
                  <ul>
                    <li>
                      Users are identifiable.
                    </li>
                    <li>
                      Users can be tracked (Signature linkable to other contexts
                      where PK is used).
                    </li>
                  </ul>
                </div>
                <div>
                  <ul>
                    <li>
                      Users are anonymous.
                    </li>
                    <li>
                      Users are unlinkable in different contexts.
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: "Tabs",
  data() {
    return {
      currentTabKey: 1,
      tabs: [
        {
          key: 1,
          icon: require("../assets/intro/icon_intro_painPoint_U@2x.png"),
          activeIcon: require("../assets/intro/icon_intro_painPoint_S@2x.png"),
          text: "Pain Points"
        },
        {
          key: 2,
          icon: require("../assets/intro/icon_intro_trust_U@2x.png"),
          activeIcon: require("../assets/intro/icon_intro_trust_S@2x.png"),
          text: "Trust Issue"
        },
        {
          key: 3,
          icon: require("../assets/intro/icon_intro_incidents_U@2x.png"),
          activeIcon: require("../assets/intro/icon_intro_incidents_S@2x.png"),
          text: "Recent Incidents"
        },
        {
          key: 4,
          icon: require("../assets/intro/icon_intro_why_U@2x.png"),
          activeIcon: require("../assets/intro/icon_intro_why_S@2x.png"),
          text: "Problems"
        },
        {
          key: 5,
          icon: require("../assets/intro/icon_intro_revenue_U@2x.png"),
          activeIcon: require("../assets/intro/icon_intro_revenue_S@2x.png"),
          text: "Benefits"
        },
        {
          key: 6,
          icon: require("../assets/intro/icon_intro_credential_U@2x.png"),
          activeIcon: require("../assets/intro/icon_intro_credential_S@2x.png"),
          text: "Credentials Comparison"
        }
      ]
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.tabs-container {
  margin-top: -60px;
  > ul {
    padding: 0 40px;
    display: flex;
    flex: nowrap;
    > li {
      position: relative;
      display: inline-block;
      font-size: 16px;
      font-family: Lato;
      font-weight: bold;
      color: rgba(80, 80, 80, 1);
      line-height: 60px;
      padding: 0 34px 0 0;
      cursor: pointer;
      height: 60px;
      white-space: nowrap;
      overflow: hidden;
      img {
        width: 24px;
        height: 24px;
        display: inline-block;
        margin-right: 10px;
        vertical-align: middle;
      }
    }
    > li.active {
      color: rgba(240, 0, 0, 1);
    }
    > li.active:after {
      content: "";
      position: absolute;
      left: 28%;
      bottom: 0;
      width: 0;
      height: 0;
      border-top: 0;
      border-left: 25px solid transparent;
      border-right: 25px solid transparent;
      border-bottom: 18px solid white;
    }
  }
  .tab-content {
    padding-bottom: 232px;
    background: url("../assets/bg/img_intro_bg.png");
    > .center-area {
      padding: 64px 0 0;
      > div {
        display: none;
        .line {
          width: 150px;
          height: 1px;
          background: #f00000;
          margin: 0 auto;
          margin-bottom: 46px;
        }
        h2 {
          font-size: 20px;
          font-family: Lato-Black;
          font-weight: 900;
          color: #1d1d1d;
          line-height: 24px;
          margin-bottom: 40px;
          text-align: center !important;
        }
        h4 {
          width: 100%;
          text-align: center;
          font-size: 18px;
          font-weight: bold;
          color: #1d1d1d;
          line-height: 24px;
          margin-bottom: 40px;
          font-family: Lato-Bold, Lato;
        }
        .fluid-container {
          display: flex;
          justify-content: space-between;
          padding: 0 77px;
          box-sizing: border-box;
          &.center {
            justify-content: center;
          }
          > div {
            max-width: 45%;
            font-size: 14px;
            font-family: Lato;
            font-weight: 400;
            color: rgba(80, 80, 80, 1);
            line-height: 22px;
            h3 {
              font-family: Lato;
              max-width: 384px;
              min-height: 22px;
              font-size: 14px;
              font-weight: bold;
              color: #1d1d1d;
              line-height: 22px;
              margin-bottom: 16px;
            }
            h3:nth-child(1) {
              font-size: 18px;
            }
            h4 {
              height: 22px;
              font-size: 16px;
              font-family: Lato;
              font-weight: bold;
              color: rgba(29, 29, 29, 1);
              line-height: 22px;
              margin-bottom: 6px;
            }
            p {
              margin-top: 20px;
            }
            .RedFont {
              height: 22px;
              font-size: 14px;
              font-family: Lato;
              font-weight: bold;
              color: rgba(240, 0, 0, 1);
              line-height: 22px;
              margin-top: 30px;
            }
            .BoldBlackFont {
              color: black;
              font-size: 14px;
            }
            ul {
              > li {
                padding-left: 18px;
                margin-bottom: 15px;
              }
            }
            > ul {
              margin-bottom: 36px;
              > li {
                list-style-type: none;
                background: url("../assets/misc/icon_misc_bullet@2x.png")
                  no-repeat 0 8px;
                background-size: 9px 7px;
                > ul {
                  > li {
                    list-style-type: none;
                    background: url("../assets/misc/icon_misc_bullet2@2x.png")
                      no-repeat 0 8px;
                    background-size: 9px 7px;
                  }
                }
              }
            }
          }
          .CenterBox {
            width: 100%;
            max-width: 70%;
            height: 280px;
            display: flex;
            flex-direction: column;
            .CenterBoxTop {
              margin-bottom: 6px;
              display: flex;
              font-size: 14px;
              font-family: Lato;
              font-weight: bold;
              height: 40px;
              color: rgba(255, 255, 255, 1);
              line-height: 40px;
              text-align: center;
              div:nth-child(1) {
                margin-right: 6px;
              }
              div {
                flex: 1;
                background: red;
              }
            }
            .CenterBoxMain {
              flex: 3;
              margin-bottom: 6px;
              background: rgba(242, 242, 242, 1);
              ul {
                margin: 0 auto;
                li {
                  list-style-type: none;
                  background: url("../assets/misc/icon_misc_bullet@2x.png")
                    no-repeat 0 8px;
                  background-size: 9px 7px;
                  margin-left: 37%;
                  height: 20px;
                  line-height: 20px;
                }
              }
            }
            .CenterBoxBottom {
              flex: 2;
              display: flex;
              div:nth-child(1) {
                margin-right: 6px;
              }
              div {
                flex: 1;
                background: rgba(242, 242, 242, 1);
                ul {
                  width: 100%;
                  height: 100%;
                  margin-top: 6px;
                  li {
                    font-size: 14px;
                    list-style-type: none;
                    background: url("../assets/misc/icon_misc_bullet@2x.png")
                      no-repeat 0 8px;
                    background-size: 9px 7px;
                    margin-left: 20px;
                    height: 20px;
                    line-height: 20px;
                  }
                }
              }
            }
          }
        }
      }
      > div.active {
        display: block;
      }
    }
  }
  .tab-font {
    width: 100%;
    font-size: 14px;
    font-family: Lato;
    font-weight: bold;
    color: rgba(29, 29, 29, 1);
    height: auto;
    margin-top: 20px;
    font-size: 18px;
  }
  .tab-font:nth-child(1) {
    margin: 0;
  }
  .tab-font:nth-child {
    color: red;
  }
}
@media screen and (max-width: 768px) {
  #item {
    .center-area {
      background: pink;
    }
  }
  .tabs-container {
    ul {
      overflow-x: auto;
      white-space: nowrap;
      padding: 0 16px;
      margin-bottom: -17px;
      li {
        overflow: initial;
      }
    }
    ul::-webkit-scrollbar {
      width: 0;
    }
    .tab-content {
      padding-bottom: 0;
      .center-area {
        padding: 48px 16px 113px;
        > div {
          .fluid-container {
            .CenterBox {
              .CenterBoxMain {
                ul {
                  li {
                    margin-left: 0;
                    width: 200px;
                    margin: 10px auto;
                  }
                }
              }
            }
            div {
              ul {
                padding: 0;
                margin-bottom: 21px;
                li {
                  white-space: normal;
                  font-size: 14px;
                  font-family: Lato-Regular, Lato;
                  font-weight: 400;
                  color: #505050;
                  line-height: 22px;
                }
              }
              h4 {
                width: 343px;
                height: auto;
                margin-bottom: 4px;
              }
              h3 {
                font-size: 14px !important;
                font-family: Lato-Bold, Lato;
                font-weight: bold;
                color: #1d1d1d;
                line-height: 22px;
              }
            }
          }
          h2 {
            text-align: left;
          }
        }
        .active {
          .fluid-container {
            display: flex;
            flex-direction: column;
            padding: 0;
            div {
              width: 100%;
              max-width: 100%;
            }
          }
        }
      }
    }
  }
}
</style>
