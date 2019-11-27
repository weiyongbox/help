# 华炎办公安全白皮书

华炎办公致力于为用户提供安全可靠的移动办公服务。信息安全是用户放心使用的基础，因此，华炎办公一直把安全作为最高优先级目标。我们的信息安全与阿里的钉钉保持高度一致，并通过多种方式、从多个层面保障企业的数据安全。华炎办公通过专门的信息安全委员会来加强信息安全体系建设，并对华炎办公业务以及整体环境安全负责。

## 数据安全

信息安全主要目标之一是保护业务系统和应用程序的基础数据安全。依据数据的安全生命周期，华炎办公对数据创建、存储、使用、共享、归档的整个过程都有相应的保护措施。

#### 数据分级
华炎办公对所有用户和企业数据提供存储安全保护。根据存储与使用的数据，实施数据等级保护策略，并按照数据价值和敏感度对数据进行等级划分。根据数据安全的分级，又对应相应的保护策略和要求，以保护用户和企业数据的安全存储。

#### 完整的操作日志记录

每一条数据导出、增删均有完整的操作日志可以查询，操作人、操作时间、操作结果一并记录在案。如有异常操作记录，能够及时发现并处理相关责任人。

## 通信安全

除了数据安全外，信息的传输安全同样重要。华炎办公采用了多种方式，从传输加密、传输保证、账户认证等多个维度来确保数据的传输安全。

#### 网络隔离

华炎办公通过不同的安全域或物理隔离的网络来实现不同级别的网络隔离。所有的用户接入请求均通过严格配置的 NAT 策略实现，所有的维护请求均通过独立网络经由 DMZ 完成。对网络的出口处通过端口镜像的方式来甄别各种网络威胁。而内部网络根据不同的用途实现物理隔离，如公共网络，存储网络，心跳网络以及管理网络。生产网络与办公网络完全隔离，并通过严格的审核机制以及上线流程来保证受信程序或端口的安全访问；同时安全专员会定期执行网络安全扫描测试以主动发现可能存在的网络隐患。已实现全站 https 的访问以防止各种网络窃听行为和流量劫持的发生。

#### 传输加密
华炎办公采取了一系列的完善措施防止通讯被监听、劫持和篡改，确保了通讯的安全。华炎办公对各项应用通讯进行了全程 SSL 加密，以保证数据安全性。除此之外华炎办公还针对每个企业设置了唯一的 token 来对通讯内容进行 AES 加密。

#### 端到端传输保证

利用对称密码技术对 IP 数据报进行加密／解密处理，使得网络中传输的 IP数据报只有通信双方能够识别，可以为互联网络上两台主机之间提供加密的安全通信。安全管理工作由独立的安全服务器完成，采用公钥密码技术向安全客户端传输安全通信所使用的对称密钥，保证端到端的传输数据传输安全。

#### DDOS 网络攻击防备

华炎办公与第三方专业防 DDoS 机构合作，对所有的入站流量实现准实时分析，对异常流量实现及时的手工阻断；与第三方的安全机构合作对关键业务服务器通过监控代理实时上报安全相关的各种数据。当攻击发生时，通过自动化的运维机制，被攻击节点将自动停止服务，并通过第三方专业防 DDoS 机构执行流量清洗后回源到华炎办公的备用节点，保障服务持续运行。

#### 双重认证

华炎办公支持双重认证，用户除使用普通的密码认证外，也可以使用企业微信的动态身份认证。当用户名和密码丢失后，用户账户和数据仍然可以得到可靠保护，避免被其他人访问。

## 系统安全

华炎办公自系统搭建时就完整考虑了系统级的安全方案，从通讯录的权限到各个应用、文档的访问都有相应的访问控制措施，在确保了外部条件的安全后进一步强化了内部安全。

#### 管理权限分级访问安全

华炎办公各个应用均有独立的访问控制鉴权功能，可以针对每一个应用、每一条数据、表单设置对应的可见范围，访问控制的精度能细化到个人或部门，其他人在非授权情况下无法访问目标数据。保存到华炎办公的信息上报、知识百科具有企业访问权限控制，即使被转发给非本企业的用户，对方也无法查看。

#### 管理员登录安全

账号安全体系依托口令策略和访问控制策略，禁用弱口令，监控非法登录尝试。同时，通过账号监测平台，对用户同设备批量尝试登录账号进行监控报警，发现攻击行为，阻止登录尝试华炎办公管理员账号还支持与通讯录用户进行绑定，绑定后登录管理后台时会收到登录提醒，如发现收到提醒却不是本人登录，管理员应及时上线修改密码。

#### 人员及流程管理制度

严格的数据访问制度：只有技术总监（公司合伙人）具有数据服务器管理权限，并且对数据服务器的维护必须由技术总监亲自操作，不得委托他人。
规范的客户服务流程：只有当客户提出需求、认可并授权时，我们的服务人员才会在客户监控下访问客户数据。一切未经客户授权的数据访问，都是被禁止的。
保密协议的商务保障: 在客户同我们签署合同的同时还会签署保密协议，确保我公司和个人不会以任何形式泄露客户数据和隐私。

## 物理安全

华炎办公数据中心包含以下标准的物理安全控制要求：

#### 高可用的分布式服务器集群

华炎办公所在数据中心配备有数十台高性能服务器组成的高性能集群，能确保所有服务的高性能运转。集群内部配有多台备用服务器节点。一旦发现故障节点，可自动接管；因此无论任何节点出现故障，都不会影响整体系统的服务。同时我们还将通过最大限度减少计划内和计划外的停机时间、不间断业务的热升级，来确保各项服务的高可用性。
-.电信级机房比企业的普通服务器机房具备更高的可用性和抗灾。
-.机房安全制度：IDC 机房对进出人员进行严格管理，配备了门禁系统，严格验证进入人员身份，保证机房空间安全性。

#### 高度冗余的硬件配备

数据中心部署的所有硬件，从防火墙、路由器、交换机，到服务器内部的网卡、电源、硬盘，核心业务及数据服务均实现冗余或主备部署，并部署在多个机房，通过多家运营商实现多链路接入；数据备份以准实时的方式同步到异地机房，确保在突发情况下，为华炎办公的持续服务提供保障。；任何一份损坏，都会自动进行切换，并可热插拔、实现在线更换。数据中心采用先进的南北智能双线互联互通方案，同时配备网通及电信专用光纤接入，中国南北及海外用户均可高速访问.

#### 健全的灾难防护措施

为保障客户 7*24*365 不间断运作，数据中心采用了全方位的防护措施，能确保华炎办公提供的服务不会因为电力故障、火灾、潮湿、高温等气候变化而受到干扰。关于数据的恢复演练及容灾备份策略，我们针对 DDoS 防御执行每季度演练；针MongoDB 利用自己的主从复制技术，采取生成多个副本（本地准实时+异地延时），实现容灾；针对文件类型的数据，利用其自身的复制技术，采取生成多个副本，并定期转储至异地机房，实现容灾。针对其余相关的涉及可用性的演练（如数据库主从切换、机房链路切换、防火墙主从切换等）不定期执行。
#### 全天候的自动备份集群

系统所在数据中心配备了强大的备份服务器集群，每天凌晨系统将数据备份到灾备中心，能实现强大的全天候自动备份，提供无中断备份和恢复过程，实现全面的数据安全保护。



 