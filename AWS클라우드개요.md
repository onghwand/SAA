# AWS 클라우드 개요

### AWS Global Infrastructure

![image-20230618135754570](/Users/admin/Desktop/SAA/AWS클라우드개요.assets/image-20230618135754570.png)

- AWS Regions

  - AWS has Regions all around the world
  - How to choose an AWS Region?
    - Compliance with data governance and legal requirements : 예를 들어 프랑스의 데이터는 프랑스 내에 -> 어플리케이션 프랑스 내에
    - Proximity to customers: reduced latency : 대부분의 사용자가 미국에 있으면 미국을 선택하는 것이 지연 시간을 줄일 수 있음
    - Available service within a Region: 모든 서비스가 모든 리전에 있지는 않을 수 있기 때문에 확인해야함
      - [리전별 AWS 서비스](https://aws.amazon.com/ko/about-aws/global-infrastructure/regional-product-services/?p=ngi&loc=4&refid=fa2d6ba3-df80-4d24-a453-bf30ad163af9)
    - Pricing: 요금은 리전마다 다름 -> 서비스 요금 페이지 참고

- AWS Availability Zones

  ![image-20230618141226450](/Users/admin/Desktop/SAA/AWS클라우드개요.assets/image-20230618141226450.png)

  - Each region has many AZ(usually 3, min 2, max 6)
  - Each AZ is one or more discrete data centers with redundant power
  - separate from each other -> isolated from disasters
  - connected with high bandwidth -> ultra-low latency networking

- AWS Data Centers

- AWS Edge Locations/Points of Presence (전송지점)

  - Amazon has 216 Points of Presence -> lower latency

