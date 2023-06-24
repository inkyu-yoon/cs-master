## 네트워크

<details>



<summary><h3> TCP와 UDP의 차이점</h3></summary>


```
// 답변

📌 TCP는 연결 지향형 프로토콜이고, 흐름제어 · 혼잡제어 · 패킷 순서 보장 등을 지원합니다.
신뢰성 향상을 위한 3-way · 4-way handshake 과정이 있어 UDP 보다는 속도가 느립니다.

📌 UDP는 비연결형 프로토콜입니다.
데이터의 수신 여부를 확인하지 않고 패킷의 순서 보장을 하지 않기 때문에 신뢰성이 낮지만 속도가 빠르다는 장점이 있습니다.
```



### 📖 **TMI**

<div align = "center">
  <img src="https://raw.githubusercontent.com/buinq/imageServer/main/img/image-20230623154540657.png" alt="image-20230623154540657" style="width: 500px;"  />
</div>


TCP와 UDP는 OSI 7 계층 중 **전송 계층에 해당하는 프로토콜**이다.

전송 계층은 신뢰성있는 데이터 전송을 담당하는 계층이다.

<br>

1️⃣ **TCP (Transmission Control Protocol)**

TCP의 전송 단위는 세그먼트라고 하며, 각 세그먼트는 헤더를 갖는다.

IP가 컴퓨터 레벨까지의 데이터의 전송을 처리한다면, TCP는 응용패킷 관리와 추적을 당담한다.

<div align = "center">
<img src="https://raw.githubusercontent.com/buinq/imageServer/main/img/image-20230623152421689.png" alt="image-20230623152421689" style="width: 500px;" />
</div>


헤더의 목적지 포트 주소를 지정해 전송한다. 예를 들어, 웹으로 접근하는 목적지 포트는 80이다.

`Sequence number` 헤더는 TCP 세그먼트의 순서번호를 표시하고 이를 통해 전송하는 패킷의 순서를 보장할 수 있다.

그리고 `CheckSum` 정보를 통해 데이터 오류가 발생했는지 검사한다.

> CheckSum은 간단히 말하면, 데이터를 더해서 만든 바이트를 이용해서, `체크섬 바이트 + (데이터 총 합 바이트) = 0` 을 만족하는 체크섬 바이트라는 것을 얻고, 데이터 전송 후에도 체크섬 바이트를 더했을 때 0이 나오는지 확인하는 것이다.

`Flags` 에는 `ACK` · `SYN` · `FIN` 과 같은 플래그 비트들이 있고 이를 통해서 연결 과정에선 3-way handShake 혹은 연결 해제 과정에 4-way handShake를 진행한다.

<br>

💡 데이터 송신 측과 수신 측의 처리 속도를 조절하여 흐름 조절을 하고 네트워크 내의 패킷 수를 조절하여 혼잡 제어를 수행한다.



🚨 단, 신뢰성을 중요시하다보니, 매번 handShake 같은 과정이 수반되므로 시간 손실이 발생하고 패킷의 전송 순서에 맞게 수신이 안되거나 손실되는 경우 재 전송함으로서 시간 손실이 발생한다는 단점이 있다. 그리고 1대1 통신만 가능하다.

<br>

2️⃣ **UDP (User Datagram Protocol)**

<div align = "center">
<img src="https://raw.githubusercontent.com/buinq/imageServer/main/img/image-20230623152255679.png" alt="image-20230623152255679"  style="width: 500px;" />
</div>


UDP도 TCP와 동일하게 포트번호를 지정하고 `CheckSum` 이 존재한다.

UDP는 신뢰성 연결보다는 빠른 전송에 중점을 둔 프로토콜이다.

따라서, 🚨 데이터의 수신 여부나 전송한 패킷 순서대로 수신되었는지 확인하지 않는다.

💡 속도가 빠르다는 이점이 있어 실시간 스트리밍, DNS(Domain Name System) 등 데이터의 신속한 전송이 중요한 비대화형 애플리케이션에 적합하다.

데이터의 순서나 신뢰성이 크게 중요하지 않고 TCP의 연결 설정과 재전송 기능이 실시간 요구사항을 충족하지 못할 수 있기 때문이다.

</details>







## 운영체제

<details>



<summary><h3> TCP와 UDP의 차이점</h3></summary>


```
// 답변

```



### 📖 **TMI**



</details>



## 데이터베이스

<details>



<summary><h3> TCP와 UDP의 차이점</h3></summary>


```
// 답변

```



### 📖 **TMI**



</details>







