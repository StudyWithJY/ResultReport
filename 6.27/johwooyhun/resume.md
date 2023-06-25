# 이력서(?)

## 소프트웨어 개발에 대한 개인적 생각
- [리처드 스톨먼](https://stallman.org)  
- [자유 소프트웨어 재단](https://fsf.org)  
소프트웨어는 사용자의 다음과 같은 자유를 존중해야한다.  
    0. 소프트웨어를 사용할 자유.
    1. 소프트웨어를 연구할 자유.
    2. 소프트웨어를 수정할 자유.
    3. 소프트웨어를 재배포할 자유.  
- [Suckless 재단](https://suckless.org)  
위와 같은 자유를 존중하기 위해선 소프트웨어가 단순해야한다. 단순해야 이해가 되고, 이해가 되어야 연구를 하고, 연구를 해야 수정하고 재배포할 수 있기 때문이다.

## DEW 프로젝트
### [Decentralized Encrypted World](https://codeberg.org/jeremiahjoh/)
현재의 World Wide Web은 사용자의 자유를 더 이상 존중하지 못한다. 사용자를 단순히 웹페이지의 소비자로만 취급하고 있으며, 그들의 개인정보를 광범위하게 수집하는 것에 비해 그 개인정보마저도 매우 무책임하게 다룬다.  
이 프로젝트는 웹 사용자의 개인정보를 보호하면서 사용자를 웹사이트의 생산자로 끌어들이는 것을 목적으로 하고 있다.  
#### 이 프로젝트를 이루는 주요 컴포넌트들.  
- Personal Database  
> 사용자의 개인정보를 사용자의 디바이스에 가두고 관리하기 위한 단순한 key-value 형태의 DB.  
- Virtual Machine  
> Personal Database와 문서를 동적으로 운영할 가상 머신.  
- Jeremiahn  
>가상 머신 위에서 작동할 단순한 형태의 절차적 프로그래밍 언어.  
- Decentralized Encrypted World  
> UDP를 기반으로 Reliable과 Best-Effort를 API레벨에서 설정하여 사용할 수 있는 Transport layer protocol과 메시형 네트워크.
- Markdown Markup Model  
> Markdown을 기반으로 만든 동적 문서.  
- III Interactive Image  
> PNG 이미지 파일을 기반으로 하는 동적 문서.(구현중)  
  
#### 컴포넌트 구조
```
+---------------------------+-----------------------+
|   Markdown Markup Model  or  III Interacive Image |
+---------------------------------------------------+
|                  Virtual Machine                  | <- Jeremiahn
+-------------------------------+-------------------+
| Decentralized Encrypted World | Personal Database |
+-------------------------------+-------------------+
```

## 앞으로의 프로젝트
- 새로운 형태의 OS Kernel
