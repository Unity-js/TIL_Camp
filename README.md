# TIL_Camp

<details>
<summary>2024.09.09 </summary>

짧은 기간이지만 처음으로 팀 프로젝트를 시작하게 되었습니다.

git 사용법에 대해서 처음에 미숙했으나 팀원분들의 도움과 직접 해 보면서 차차 손에 익어갔습니다.

프로젝트에서 사운드 관련 작업을 맡아, 기존 카드 게임에서 변경할 것들은 변경하고, 추가 할 것들은 추가하는 작업을 완료했습니다.

역할 분담을 맡아서 팀원분들 각자 맡은 임무를 잘 수행해주셨고, 내일 마무리와 추가적인 기능을 손보면 될거 같습니다.

튜터님께 조언들은대로 Unity는 영어로 사용하는데 익숙 해져야 할 것 같습니다. 

```
오늘자 스크립트 및 파일 수정

GameManager 와 Card 에 있는 Audioclip 변경 및 추가
(카드 뒤집기, 일치시, 불일치시, BGM 수정 및 추가)

사운드 파일 프로젝트 내 삽입 및 push
(추가적인 기능을 위한 사운드 추가 / 카드 셔플, 제한시간)

내일 추가 할 것
제한시간 X초 남았을시 타이머 스크립트 제한시간, 사운드 추가
카드 셔플 스크립트 , 셔플 사운드 추가
추가적으로 챌린지 탭에 있는 부가 기능들 구현하기

```
</details>

<details>
<summary>2024.09.10 </summary>

어제 작업 하던 것들을 마무리하고, 오늘 팀원분들의 노력 덕에 큰 틀은 완성되었습니다.

팀 세션에 있는 챌린지 (부가기능)들을 각자 맡으며 하나 하나씩 코딩해보고, 수정하고, 의견을 나누며 추가해갔습니다.

처음으로 push 하는 과정에서 충돌이 일어나게 되었는데, Dev2에 올렸던 걸 새로 올라온 코드와 비교해보고 추가해가며 오류 없이 제대로 작동하게 되었습니다.

오늘자 수업이 끝나기 전 잊었던 카드 셔플시에 사운드를 추가 하려 했는데, board 스크립트에서 audioclip이 불러와지지 않는 거 같아 튜터님께 여쭤볼 예정입니다.

ㄴ 질문 후 기록

```
오늘자 스크립트 및 파일 수정

와이어프레임 초안 작성 완료

모든 난이도에서 TimeTxt가 10초 남았을때, 플레이어에게 경고음이 출력되게 추가

레벨 1, 레벨 2, 레벨 3 각각 난이도에서 카드들의 총 배열 수를 4*4 4*5 4*6의 순서로 추가 및 스케일 조정
ㄴ 각각의 부족한 이미지 추가 및 Board 에러 수정

내일 추가 할 것
Board 에서 카드를 셔플 할때 사운드 출력
ㄴ 튜터님께 여쭤보기
남은 챌린지 기능들 토의 후 추가하기
```
</details>

<details>
<summary>2024.09.11 </summary>

3일에 걸쳐서 큰 틀을 만들고, 기능들을 추가하며 최종적으로 작업을 마무리 했습니다.

어제 여쭤보기로 했던 사운드쪽 문제는 빈 오브젝트 생성으로 외부 함수를 불러 오는 것으로 해결했습니다.

그리고 변경된 코드를 받아오는 과정에서 사운드쪽 버그가 발생해 수정해주었습니다.

곧 있을 발표를 위한 ppt에 넣을 와이어 프레임 초안도 정리해서 업로드했습니다.

그리고 개인 면담을 가지게 되었는데, 여러가지 질문들에 자세히 대답해주셔서 큰 도움이 되었습니다.

```
오늘자 스크립트 및 파일 수정

각 레벨씬에서 카드 셔플 시 사운드 적용추가, 사운드 재생 안되던 버그 수정

새로운 코드를 받아오는 과정에서 카운트 다운이 작동하지 않는 버그 수정

End Text 수정
```
</details>

<details>
<summary>2024.09.12 </summary>

팀 프로젝트가 완성되었기에 내일 발표를 위해 ppt를 준비하고 그에 들어갈 내용들을 정리해서 기재했습니다.

인게임 플레이 영상도 자잘한 버그들을 수정해가며 업로드했습니다.

초기 상태의 녹화를 위해 기존 level 들이 해금 되어 있어, playerPrefbs 를 초기 상태로 돌리는 스크립트를 작성했습니다.

추가로, 카드 매치시 시간을 5초 추가해주는 시스템으로 level 3 의 높은 난이도를 밸런스 맞게 fix 했습니다.

남은 시간에 개인 공부 및 팀 프로젝트 발표를 위한 구상을 하였습니다.

```
오늘자 스크립트 및 파일 수정

초기 상태 인게임 녹화를 위해 유니티 창에서 playerPrefbs를 초기화 할 수 있게 editor 폴더쪽 스크립트 추가

파일 수정 없음

```
</details>

<details>
<summary>2024.09.13 </summary>

오늘을 마지막으로 1주일의 첫 팀 프로젝트를 마무리 짓게 되었습니다.

팀원분들이 각자의 역할을 너무 잘 구현해주셨기에 많은 PPT 내용을 다 소개하기에는 시간이 부족해, 발표 때에 차마 다 소개하지 못한거 같고 말을 빠르게 한 거 같아 아쉬웠습니다.

다른 조 분들의 게임도 설명을 듣고, 직접 보고 나니 제 개인적인 역량을 더 키우고 싶다는 생각이 들었습니다.

오늘 전체 조 분들의 발표가 끝나고 개인에게 할당된 시간이 많았기에, 팀원분들과 인사를 하고, 다음 주에 있을 C# 관련 자료들을 예습하는 시간을 가졌습니다.

몇 년전에 배워서 그런지 C 와는 한참 다른 느낌이였기에 강의를 보면서 공부를 많이 해야 할 것 같았습니다.

그래도 유니티에서 결국 사용하기에 어느 정도 다루기에 편해질때까지 열심히 하려고 합니다.

팀 프로젝트 진행하신 모든 분들 고생 많으셨습니다. :clap::clap::clap:

```
오늘자 스크립트 및 파일 수정

없음

```

</details>

<details>
<summary>2024.09.19 </summary>


이번 주부터 본격적으로 C# 프로그래밍을 배우기 시작했습니다.

10시부터 어떤 걸 공부하는지, 이번에 제출하게 될 과제는 무엇인지 알려주셨고, 2시부터 C# 체크리스트 강의를 들었습니다.

자료형과 변수에 관련해서 다른 예시를 들어주고, 알기쉽게 설명해주셔서 이해하는데 편했습니다.

그 후에, 1주차와 2주차 강의를 듣고 과제를 제출했습니다.

주로 강의 내용에 나온 변수, 자료형을 이용한 것과 반복문이 위주가 되어서 반복문에서 처음엔 조금 헷갈리긴 했지만 앞으로 자주 쓰게 될 거 같아 열심히 공부했습니다.

배열도 많이 파봐야 할 거 같습니다. 처음엔 그냥 특정값을 나열하는 용인줄 알았는데, 그 안에서 랜덤적인 것도 할 수 있고, 
배열의 순서에서 가져 오는 것도 가능 하다는 것을 배워서 개인 과제에 유용하게 사용 할 수 있을거 같습니다.

그리고 새로운 팀 프로젝트를 진행하게 되어 팀명과 팀 세션을 작성했습니다.
  
</details>

<details>
<summary>2024.09.20 </summary>

오늘도 마찬가지로 개인 공부를 하며 C# 체크리스트 2번째 강의를 들었습니다.

매개변수는 아직 헷갈리긴 하지만 튜터님이 진행하신 강의로 이해하게 되었습니다.

TIL 강의에서는 전 기수 분의 우수 TIL을 보게 되었습니다. 제가 기존에 생각하던 느낌이랑 많이 달라서 차차 캠프를 보내면서, 기술적인 부분에서
TIL을 다듬어 나가야 할 거 같습니다.

그리고 2주차 숙제를 어제 끝내지 못해서 숫자 맞추기 , 틱택토 게임을 구현했습니다.

틱택토 게임에서 배열을 주로 사용 하였는데 이차원 배열을 구현하는 과정에서 이중 반복문을 사용해, 보기 편하게 그리고,
while 문에 조건으로 논리 연산자를 추가해서 번갈아 입력할 수 있도록 구현했습니다.

bool 값을 이용하는게 코드를 좀 더 간소화 하는데 도움이 될거 같아 적용 해 보았습니다.

```C
// 틱택토 2차원 과제 연습

string[] tile = new string[9] { "1", "2", "3", "4", "5", "6", "7", "8", "9" };

bool playerturn = true;
int numturn = 0;

while (!Wincheck() && numturn != 9)
{
    Tile();

    if (playerturn)
    {
        Console.WriteLine("플레이어1 의 턴입니다.");
    }
    else
    {
        Console.WriteLine("플레이어2 의 턴입니다.");
    }

    string select = Console.ReadLine();

    if (tile.Contains(select) && select != "X" && select != "O")
    {
        int tileinfo = Convert.ToInt32(select) - 1;

        if (playerturn)
        {
            tile[tileinfo] = "X";
        }
        else
        {
            tile[tileinfo] = "O";
        }

        numturn++;
    }

    playerturn = !playerturn;
}

if (Wincheck())
{
    Console.WriteLine("승리!");
}

else
{
    Console.WriteLine("무승부!");
}

bool Wincheck()
{
    bool row1 = tile[0] == tile[1] && tile[1] == tile[2];
    bool row2 = tile[3] == tile[4] && tile[4] == tile[5];
    bool row3 = tile[6] == tile[7] && tile[7] == tile[8];
    bool column1 = tile[0] == tile[3] && tile[3] == tile[6];
    bool column2 = tile[1] == tile[4] && tile[4] == tile[7];
    bool column3 = tile[2] == tile[5] && tile[5] == tile[8];
    bool diagonal1 = tile[0] == tile[4] && tile[4] == tile[8];
    bool diagonal2 = tile[6] == tile[4] && tile[4] == tile[2];

    return row1 || row2 || row3 || column1 || column2 || column3 || diagonal1 || diagonal2;
}

void Tile()
{
    for (int i = 0; i < 3; i++)
    {
        for (int j = 0; j < 3; j++)
        {
            Console.Write("|" + tile[i * 3 + j] + "|");
        }

        Console.WriteLine();
    }
```

</details>

<details>
<summary>2024.09.23 </summary>

수요일 있을 개인 과제 제출을 위해 C# 강의를 4주차까지 전부 듣고 이해가 되지 않는 부분들을 복습하며 진행했습니다.

주로 정리 한 것들

객체 지향 프로그래밍의 5가지 구성요소, 클래스의 구성요소 이때 > 구조체와의 차이점 

구조체에서는 Person p; 였으나 
클래스는 Person p = new Person();

왜? 클래스는 레퍼런스 타입임.
구조체에서의 value type의 변수를 다른 변수에 할당하면 해당 값의 복사본이 생성, 별도의 메모리 공간에 저장되기에 원본과 서로 독립적이지만, Reference Type 에서는 메모리 주소의 참조가 복사됨, 따라서 두 변수는 같은 객체를 참조하게 됨
그래서 객체화를 진행 해야 함

구조체는 상속 x 
작은 크기의 데이터, 단순한 구조는 구조체
좀더 복잡한 객체 표현, 다양한 기능은 클래스


생성자
객체가 처음 생성될때 초기화, 필요한 초기값을 설정함
여러개 정의 가능 , 매개변수의 개수와 타입에 따라 다른 생성자 호출 가능 (오버로딩)

기본적으로 디폴트 생성자가 자동으로 생성되지만 직접 정의할 경우 자동으로 생성되지 않음.

소멸자
클래스와 동일한 이름을 가지고, 이름 앞에 ~ 기호를 붙여서 표현
C#의 경우 가비지 컬렉터에 의해 관리되는 메모리 해제를 담당하므로, 명시적으로 소멸자를 호출하는것을 권장하지 않음

프로퍼티 Property
객체의 필드에 직접접근하지 않고 간접적으로 값을 설정하거나 읽을수 있게함

[접근 제한자] [데이터 타입] 프로퍼티명
{	get
	{
		// 필드를 반환 or 다른 로직 수행
	}
	set 
	{ 
		// 필드 값 설정 or 다른 로직 수행
	}
}


자동 프로퍼티

필드의 역할도 같이 진행이 됨

[접근 제한자] [데이터 타입] 프로퍼티명 { get; set; } 
우선 만들어놨다가 필요할때 분리해서 사용하는 것도 가능하므로 미리 구현 해 놓는 것이 좋음

결론 : 객체 지향 프로그래밍의 원칙 5가지를 지켜주는것이
유지보수를 하기 위해 좋다

프로퍼티를 사용해 필드접근을 제어하면, 코드의 안정성, 가독성 상승

클래스 접근 제한자를 적절히 사용해 필요한 부분만 외부에서 접근하도록 설정 (어느 정도 보안을 생각해야 하므로)

상속
코드의 재사용, 계층 구조 표현, 유지보수 향상

단일 상속
다중 상속 : c#에서는 미지원이나, 인터페이스 상속에서는 가능
인터페이스 상속 

public class 자식클래스명 : 부모클래스명

상속을 하더라도 같은 함수명에 대해 재정의를 하면
자신이 우선순위가 됨. (비권장)

가상 메서드
자식클래스에서 재정의를 했을수 있다.
virtual >> 실형태가 다를 수 있으니, 재정의가 되어있는지 확인하라는 뜻

override

추상 클래스
abstract 
상속 받은 클래스에 무조건 재정의 되어 있다고 강제성을 부여

virtual 과 abstract 는 권한의 차이가 있음

<오버라이딩>
부모클래스에서 정의된 메서드를 자식클래스에서 재정의 하는 것
ㄴ 함수를 덮어쓰기 하는 것

<오버로딩> 
동일한 이름의 메서드들이 매개변수의 갯수나 타입, 순서가 다른 여러개의 메서드를 정의 하는 것
즉 함수를 읽어올때 골라서 읽어올수있게 해주는 것
ㄴ 함수를 읽어올때 쓰는 것


</details>

<details>
<summary>2024.09.24 </summary>

인터페이스와 열거형

다중 상속을 사용하지 않는 이유

1. 다이아몬드 문제
한 클래스에서 두개 이상의 부모클래스로부터 동일한 멤버를 상속 받을수 있으나, 이 경우 같은 이름의 멤버를 갖고 있으면 어떤 부모 클래스의 멤버를 사용해야하는지 모르기때문

2. 설계의 복잡성
이로 인해 클래스간 상속 관계를 파악하기 어렵고 코드
유지 보수성 저하

3. 이름 충돌, 충돌 해결의 어려움
여러 부모클래스로부터 상속받은 멤버들이 이름이 충돌 할 수 있음
 
4. 그러므로 c#에서는 일관성과 단순성을 유지하고있다
결론 클래스관의 관계를 명확하게 만든다.


인터페이스를 사용하는 이유

코드 재사용성 , 다중 상속 제공, 
유연한 설계 (실제 구현은 클래스가 하므로)


<인터페이스>
클래스가 구현해야하는 멤버를 정의하는 것
클래스의 일종은 아니고, 클래스에 대한 제약조건 정도?
클래스가 인터페이스를 구현 할 경우 , 모든 인터페이스멤버를 구현 해야 함
다중 상속이 가능하다

사용 방법
interface Ixxxxx 대부분 대문자 I로 시작함
상속과 크게 다르지 않음

인터페이스와 추상 클래스의 차이점

인터페이스 : 추상적인 동작만 정의함 , 다중 상속 가능
추상 클래스 : 일부 동작의 구현을 가짐, 단일 상속만 가능


<열거형>
1. 가독성 : 연관된 상수를 명명할수 있음
2. 자기 문서화 : 의미있는 이름을 사용해 가독성을 향상
3. 스위치문과 쓸때 깔끔하고 호환성이 좋음

서로 관련된 상수들의 집합을 정의
열거형의 각 상수는 정수값

Enum

예외 처리

프로그램 실행중 발생하는 예기치 않은 상황
즉 종료나 멈추는 상황

이를 대비하기 위해 예외 처리를 진행해주며, 예외가 발생했을때는 관련된 문구를 띄운다거나.

안정성이 높아지고 디버깅이 가능해짐.

try-catch

예외처리 ㅇ 발생 ㅇ 탐지 ㅇ 
순서대로 catch 블록이 실행됨

다중 catch 블록도 가능

예외 객체
예외에 대한 정보를 엑세스 할 수 있음

finally 블록
예외 발생여부와 관계없이 무조건 실행됨, try-catch 블록뒤에
작성되며, 생략할수도 있음

사용자 정의 예외 처리
Exception 클래스를 상속받아 작성하면됨


박싱과 언박싱

박싱 : 값형을 참조형으로 변환하는 과정

언박싱 박싱된 객체를 다시 값형으로 변환하는 과정

값형> 참조형일때 값형이 사라지지않고 새롭게 변하는것이므로 메모리를 사용해, 성능저하가 발생할 수 있음

할당된 객체가 참조가 없을경우 가비지 컬렉션이 삭제함

예외처리를 할때 가능하면 구체적인 예외 클래스를 사용
이래야 안정적이고 예외 상황에 대한 처리가 정확해짐
성능면에서 차이가 생김.

</details>

<details>
<summary>2024.09.25 </summary>

클래스에 플레이어의 특성값을 저장

class jobs
{
    public int level = 01;
    public string name;
    public string job;
    public float atk = 10;
    public float def = 5;
    public float hp = 100;
    public float gold = 1500;
    public int clearcount = 0;
}


메인으로 이루어지는 곳

while 안에서 int 값을 입력 받고, 입력 받은 int 값에 따른 이벤트가 발생

while (true)
{
    Console.WriteLine("\n직업을 설정해주세요.\n\n1. 전사\n\n2. 마법사");
    int jobnum = int.Parse(Console.ReadLine());


    switch (jobnum)
    {
        case 1:
            job.job = "전사";
            break;

        case 2:
            job.job = "마법사";
            break;

        default:
            Console.WriteLine("1 또는 2를 입력해주세요\n");
            continue;
    }
    break;
}

while (true)
{
    Console.WriteLine("\n이곳에서 던전으로 들어가기전 활동을 할 수 있습니다.\n\n1. 상태보기\n\n2. 인벤토리\n\n3. 상점\n\n4. 휴식하기\n\n5. 던전 입장\n\n원하시는 행동을 입력해주세요.");

    int action = int.Parse(Console.ReadLine());

    if (job.clearcount == job.level)
    { 
        job.level += 1;
        job.atk += 0.5f;
        job.def += 1.0f;
        job.clearcount = 0;
    }

// 부가기능 플레이어 레벨 상승 시 스탯 상승 

    switch (action)

 	case 1 ...... 


if (intrss == 1)
{
    if (purchaseq[0] == true)
    {
        Console.WriteLine("판매를 완료했습니다.");
        purchaseq[0] = false;
        if (equipq[0]) equipq[0] = false; job.def -= 5;
        job.gold += 850;
        break;
    }
    else
    {
        Console.WriteLine("아이템을 보유하고 있지 않습니다.");
        break;
    }

//아이템 판매 트리거



if (job.def < 5)
{
    if (failchance <= 4)
    {
        Console.WriteLine("던전 공략에 실패했습니다.");
        job.hp /= 2;
    }
    else
    {
        Console.WriteLine("던전 클리어\n축하합니다!!\n쉬운 던전을 클리어하였습니다.\n[탐험 결과]\n");
        Console.WriteLine($"체력 {job.hp}-> ");

        Random random1 = new Random();

        int damage = random1.Next(20 + (int)job.def - 5, 36 + (int)job.def - 5);

        job.hp -= damage;

        Console.WriteLine($"{job.hp}\n");

        Console.WriteLine($"Gold {job.gold}-> ");

        job.gold += 1000.0f;

        Random random2 = new Random();

        int bonusgoldrad = (int)job.atk;

        float bonusgold = random2.Next(bonusgoldrad, 21);

        job.gold += 1000.0f * (bonusgold * 0.01f);

        Console.WriteLine($"{job.gold}\n");

        job.clearcount += 1;

        if (job.hp <= 0.0f)
        {
            Console.WriteLine($"{job.name}님이 사망하셨습니다.");
            Environment.Exit(0);
        }

        while (true)

        {
            Console.WriteLine("\n0. 나가기\n원하시는 행동을 입력해주세요.");

            int intrss = int.Parse(Console.ReadLine());

            if (intrss != 0) Console.WriteLine("상호작용에 맞는 숫자를 입력해주세요.");

            if (intrss == 0) break;
        }
    }
} // 던전 (쉬움) 입장 트리거 , 방어력 비교 후 계산 , 공격력에 따른 추가 골드 계산 , 체력 0이하 일시 사망 후 프로그램 종료

</details>

<details>
<summary>2024.09.26 </summary>

팀 프로젝트 2주차 Text RPG

```C

namespace TextRPG
{
    internal class Stageinfo
    {
        public class StageInfo
        {
            // mob 쪽 코드 작성되면 옮길 곳 , 지금은 출력을 위한 예시

            public static string[] mobname = new String[] { "name1", "name2", "name3" }; // 몹 이름
            public static int[] moblevel = new int[] { 1, 2, 3 }; // 몹 레벨
            public static int[] mobatk = new int[] { 1, 2, 3 }; // 몹 공격력
            public static int[] mobdef = new int[] { 1, 2, 3 }; // 몹 방어력
            public static int[] mobhp = new int[] { 1, 2, 3 }; // 몹 체력


            public int stagecount = 1; // 스테이지
            public static void MobCount() // 몹 종류, 수 랜덤 함수
            {
                Random random = new Random();

                int mobcount = random.Next(1, 4); // 등장하는 몹의 수

                while (!(mobcount < 1))
                {
                    Random random1 = new Random();

                    int mobtype = random1.Next(0, 3); // 등장하는 몹의 종류

                    Console.WriteLine("Lv:" + moblevel[mobtype] + mobname[mobtype] + "Hp:" + mobhp[mobtype]); // 출력

                    mobcount--;
                }

            }
        }

    }
}


```
</details>

<details>
<summary>2024.09.27 </summary>

```C

namespace TextRPG
{
    public class StageInfo
    {
        public int stagecount = 1; // 스테이지, 전투 쪽 코드에서 승리시 > 이 값 ++

        public List<Monster> monsters = new List<Monster>();

        public int[] MobCount() // 몹 랜덤
        {
            Random random = new Random();

            int mobcount = random.Next(1, 4); // 등장하는 몹의 수

            return MobReturn(mobcount);
        }

        public void Init()
        {
            int[] arr = MobCount();

            Random random = new Random();

            for (int i = 0; i < arr.Length; i++) // arr (return 받아온 배열)로 몹 종류 정하기
            {
                if (arr[i] == 0)
                {   
                    int moblevel = random.Next(1, 5); // 레벨 1~4 랜덤

                    monsters.Add(new Ork(moblevel, "Ork"));
                }
                else
                {   
                    int moblevel = random.Next(1, 5); // 레벨 1~4 랜덤

                    monsters.Add(new Goblin(moblevel, "Goblin"));
                }


            }
        }

        public int[] MobReturn(int mobCount)
        {
            int[] mobArray = new int[mobCount];

            for (int i = 0; i < mobCount; i++)

            {
                Random random = new Random();

                int mobtype = random.Next(0, 2); // 등장하는 몹의 종류

                mobArray[i] = mobtype;
            }

            return mobArray;
        }

    }

}


```

기존 코드 일부 간략화 , return 사용해서 배열에 랜덤 값을 대입하고 몹 랜덤으로 배치
버그 수정

</details>

<details>
<summary>2024.09.30 </summary>

Dungeon Scene 일부분 발제 
어제 작업하던 Stageinfo 마무리, DungeonScene 초입부 완성

> 현재 전투 진행시 작업 중
> 튜터님께 방문해서 기존에 있던 2개 수정 및 피드백

```C
namespace TextRPG
{
    public class DungeonScene : BaseScene, IMainScene
    {
        private int shiftCount;
        public override void Load()
        {
            Console.WriteLine("던전에 오신 여러분 환영합니다.");
            Console.WriteLine("이제 전투를 시작할 수 있습니다.\n");
            Console.WriteLine("1. 전투 시작");
            Console.WriteLine("2. 재정비\n");

            ConsoleKeyInfo keyInfo = Console.ReadKey(true);

            switch (keyInfo.Key)
            {
                case ConsoleKey.D1:
                    GameManager.Stage.Spawn();
                    InDungeon();
                    break;

                default:
                    GameManager.Scene.OpenScene(SceneType.Lobby);
                    break;
            }
        }


        public void InDungeon() // 던전 함수
        {
            Console.Clear();

            int mobcount = GameManager.Stage.MobCount().Length;

            Player player = GameManager.player;

            while (true)
            {
                Console.ForegroundColor = ConsoleColor.DarkYellow;
                Console.WriteLine("Battle!\n");
                Console.ResetColor();

                for (int i = 0; i < mobcount; i++)
                {
                    try
                    {
                        if (GameManager.Stage.monsters[i].IsDead)
                        {
                            Console.ForegroundColor = ConsoleColor.DarkGray;
                            Console.WriteLine($"Lv.{GameManager.Stage.monsters[i].Level} {GameManager.Stage.monsters[i].Name} Dead");
                            Console.ResetColor();
                        }
                        else
                        {
                            Console.WriteLine($"Lv.{GameManager.Stage.monsters[i].Level} {GameManager.Stage.monsters[i].Name} Hp {GameManager.Stage.monsters[i].Health}");
                        }
                    }

                    catch { } // 예외처리
                }

                Console.ResetColor();

                Console.WriteLine("\n\n[내정보]\n");

                Console.Write("Lv. " + GameManager.player.level);
                Console.Write("  " + GameManager.player.playerName + " " + "(" + GameManager.player.playerJob + ")" + "\n"); //  job "전사" 로 고정되어있음

                Console.WriteLine("Hp " + $"{GameManager.player.playerCurHealth}" + "/" + $"{GameManager.player.playerMaxHealth}" + "\n");

                Console.WriteLine("대상을 선택해주세요.\n");

                ConsoleKeyInfo keyInfo = Console.ReadKey(true);

                Random random = new Random();

                int atkdamage = random.Next(GameManager.player.playerAttack - GameManager.player.playerAttack / 10, (GameManager.player.playerAttack + GameManager.player.playerAttack / 10) + 1);

                // 공격력 10% +- 오차범위 랜덤

                switch (keyInfo.Key)
                {
                    case ConsoleKey.D1: // 1번 몹 선택시

                        if (!GameManager.Stage.monsters[0].IsDead)
                        {
                            Console.Clear();

                            int mobCurHealth = GameManager.Stage.monsters[0].Health; 

                            Console.WriteLine(GameManager.player.playerName + "의 공격!");

                            GameManager.Stage.monsters[0].Health -= 5 * atkdamage; // 테스트용 공격력 수정할것

                            Console.WriteLine($"Lv.{GameManager.Stage.monsters[0].Level} {GameManager.Stage.monsters[0].Name} 을(를) 맞췄습니다. [데미지 : " + atkdamage + "]");

                            if (GameManager.Stage.monsters[0].Health > 0)
                            {
                                Console.WriteLine("Hp " + mobCurHealth + " -> " + $"{GameManager.Stage.monsters[0].Health}\n\n");

                                int playerCurHealth = GameManager.player.playerCurHealth; 

                                Thread.Sleep(500);

                                Console.WriteLine($"Lv.{GameManager.Stage.monsters[0].Level} {GameManager.Stage.monsters[0].Name} 의 공격!");

                                Console.WriteLine(GameManager.player.playerName + "을(를) 맞췄습니다. [데미지 : " + GameManager.Stage.monsters[0].Attack + "]");

                                GameManager.player.playerCurHealth -= GameManager.Stage.monsters[0].Attack;

                                Console.Write("Lv. " + GameManager.player.level + " " + GameManager.player.playerName);

                                Console.WriteLine("Hp " + playerCurHealth + " -> " + $"{GameManager.player.playerCurHealth}\n");

                                Thread.Sleep(500);
                            }
                            else
                            {
                                Console.WriteLine("Hp " + mobCurHealth + " -> " + "Dead\n\n");

                                // GameManager.Stage.monsters[1].IsDead = true;
                            }
                        }
                        else
                        {
                            Console.Clear();
                            Console.ForegroundColor = ConsoleColor.Red;
                            Console.WriteLine("올바른 대상을 지정해주세요.\n");
                            Console.ResetColor();
                            continue;
                        }

                        break;

```

</details>

<details>
<summary>2024.10.01 </summary>

```C

namespace TextRPG
{
    public class DungeonScene : BaseScene, IMainScene
    {
        private int shiftCount;

        List<Monster> monsters = GameManager.Stage.monsters;
        private int MonsterIndex = 0;

        Player player = GameManager.player;
        public override void Load()
        {
            Console.WriteLine("던전에 오신 여러분 환영합니다.");
            Console.WriteLine("이제 전투를 시작할 수 있습니다.\n");
            Console.WriteLine("1. 전투 시작");
            Console.WriteLine("2. 재정비\n");

            int input = Input.InputKey(2, 1);

            switch (input)
            {
                case 1:
                    GameManager.Stage.Spawn();
                    InDungeon();
                    break;
            }

            GameManager.Scene.OpenScene(SceneType.Lobby);
        }
        public void InDungeon() // 던전 함수
        {
            Player player = GameManager.player;
            Random random = new Random();
            int input = 0;

            Console.Clear();

            while (true)
            {
                if (player.playerCurHealth <= 0)
                {
                    Console.WriteLine("체력이 부족해 던전에 입장 할 수 없습니다.\n\n1. 나가기\n"); // 체력 <= 0 입장제한

                    input = Input.InputKey(1, 1);
                    break;
                }

                Print.ColorPrintScreen(ConsoleColor.DarkYellow, "Battle!\n");

                for (int i = 0; i < monsters.Count; i++)
                {
                    if (monsters[i].IsDead)
                    {
                        Print.ColorPrintScreen(ConsoleColor.DarkGray, $"Lv.{monsters[i].Level} {monsters[i].Name} Dead");
                    }
                    else
                    {
                        Console.WriteLine($"Lv.{monsters[i].Level} {monsters[i].Name} Hp {monsters[i].Health}");
                    }
                }
                Console.WriteLine("\n\n[내정보]\n");

                Console.WriteLine($"Lv. {player.level} {player.playerName} {player.playerJob}");

                Console.WriteLine($"Hp {player.playerCurHealth} / {player.playerMaxHealth}\n");

                Console.WriteLine("대상을 선택해주세요.\n");

                input = Input.InputKey(monsters.Count, 1);

                int atkdamage = random.Next(player.playerAttack - player.playerAttack / 10, (player.playerAttack + player.playerAttack / 10) + 1);

                // 공격력 10% +- 오차범위 랜덤

                PlayerAttack(atkdamage, input - 1);

                if (monsters.All(alldead => alldead.IsDead)) // 모든 몹 죽었을때 로비로 돌아가기
                {
                    Console.WriteLine("\n1. 나가기\n");

                    input = Input.InputKey(1, 1);
                    break;
                }

                if (player.playerCurHealth <= 0) // 플레이어가 죽었는지 확인
                {
                    Console.WriteLine($"{player.playerName}이(가) 쓰러졌습니다!");

                    Console.WriteLine("\n1. 나가기\n");

                    GameManager.player = GameManager.Save.Load<Player>();

                    input = Input.InputKey(1, 1);
                    break;
                }
            }
        }

        public void PlayerAttack(int atkdamage, int index) // 플레이어 공격 함수
        {
            Player player = GameManager.player;

            if (monsters[index].IsDead)
            {
                Console.Clear();
                Print.ColorPrintScreen(ConsoleColor.Red, "올바른 대상을 지정해주세요.\n");
                return;
            }

            Console.Clear();

            int mobCurHealth = monsters[index].Health;

            Print.PrintScreenAndSleep($"{player.playerName} 의 공격!\n");

            monsters[index].Health -= atkdamage; // 테스트 시 공격력 수정하는 곳

            Console.WriteLine($"Lv.{monsters[index].Level} {monsters[index].Name} 을(를) 맞췄습니다. [데미지 : {atkdamage}]");

            if (monsters[index].Health <= 0)
            {
                Print.ColorPrintScreen(ConsoleColor.DarkGray, $"Hp {mobCurHealth} -> Dead\n");
            }
            else
            {
                Console.WriteLine($"Hp {mobCurHealth} -> {monsters[index].Health}\n");
            }

            Thread.Sleep(500);
            MonsterAttack();
        }

        public void MonsterAttack() // 몹 공격 함수
        {
            for (int i = 0; i < monsters.Count; i++) // 살아있는 몬스터 찾아서 공격 시도할때까지 반복
            {
                if (monsters[MonsterIndex].IsDead) // 현재 몬스터가 살아있다면 공격 진행
                {
                    MonsterIndex %= monsters.Count;
                    MonsterIndex++;
                    break;
                }
            }

            Player player = GameManager.player;

            int playerCurHealth = player.playerCurHealth;

            Console.WriteLine();

            Print.PrintScreenAndSleep($"Lv.{monsters[MonsterIndex].Level} {monsters[MonsterIndex].Name} 의 공격!\n");

            Console.WriteLine($"{player.playerName} 을(를) 맞췄습니다. [데미지 : {monsters[MonsterIndex].Attack}]");

            player.playerCurHealth -= monsters[MonsterIndex].Attack;

            Console.Write($"Lv. {player.level} {player.playerName} ");

            if (player.playerCurHealth <= 0)
            {
                Print.ColorPrintScreen(ConsoleColor.DarkGray, $"Hp {playerCurHealth} -> Dead\n");
                player.playerCurHealth = 0;
                return;
            }

            Console.WriteLine($"Hp {playerCurHealth} -> {player.playerCurHealth}\n");

            Thread.Sleep(500);
            
            MonsterIndex = (++MonsterIndex) % monsters.Count;

            if (monsters.All(alldead => alldead.IsDead))
            {
                Console.Clear();
                Print.ColorPrintScreen(ConsoleColor.Green, "Win!\n");
            }

        }
    }
}


```

DungeonScene 완료 , 부가적으로 print.cs 와 input.cs 응용을 위한 공부

내일 stageinfo 쪽 stage 추가, 클리어 보상 추가까지

</details>

<details>
<summary>2024.10.02 </summary>

```C
using System;
using System.Text; // UTP-8 이모지 때문에 사용

namespace TextRPG
{
    public class GamblingScene : BaseScene
    {
        private static readonly string[] emoji = { "7️", "💀", "🌸", "🌟", "❄️" };

        private Random random = new Random();
        public override void Load() // 메인 함수
        {
            Player player = GameManager.player;

            Console.OutputEncoding = Encoding.UTF8; // 이모지 안나오는거 방지

            Print.ColorPrintScreen(ConsoleColor.Yellow, "도박장에 오신 것을 환영합니다!\n");

            Print.ColorPrintScreen(ConsoleColor.Yellow, "500 Gold를 내고 슬롯머신을 1회 사용 할 수 있습니다.\n");

            Print.ColorPrintScreen(ConsoleColor.Yellow, "성공시 배팅금 5배! 잭팟시 배팅금 10배!\n");

            Print.ColorPrintScreen(ConsoleColor.Yellow, $"현재 소지금 : {player.playerGold} Gold\n");

            Console.WriteLine("\n----- 슬롯 머신 ------");
            Console.WriteLine($"    | 7 | 7 | 7 |");
            Console.WriteLine("----------------------\n");

            bool replay = true; // 게임 반복 여부

            while (replay)
            {
                replay = PlayGambling(); // 슬롯 머신 게임 실행
            }

            GameManager.Scene.OpenScene(SceneType.Lobby); // 필요할때 주석
        }

        private bool PlayGambling() // 게임 진행
        {
            Console.WriteLine("\n슬롯 머신을 돌리시겠습니까? \n\n1. 예\n\n2. 나가기\n");

            int input = Input.InputKey(2, 1);

            switch (input)
            {
                case 1: break; // 슬롯 머신 돌리기
                case 2: return false; // 로비로 돌아가기
            }

            Console.Clear();

            string[] result = Roll(); // Roll() 값 결과에 넣기

            Resultprint(result); // 결과 출력

            GamblingResult(result); // 잭팟 체크

            return true; // 다시 게임을 할 수 있도록 true 반환
        }

        private string[] Roll() // 무작위 이모지 산출 후 배열에 넣기
        {
            Player player = GameManager.player;

            if (player.playerGold >= 500)
            {
                player.playerGold -= 500;

                string[] result = new string[3]; // 결과 저장

                for (int i = 0; i < result.Length; i++) // 랜덤으로 기호 선택
                {
                    result[i] = emoji[random.Next(emoji.Length)]; // 0 > 길이까지
                }
                return result; // 반환
            }

            else // 소지금 없을때 예외처리
            {
                Console.SetCursorPosition(0, 8);
                Print.ColorPrintScreen(ConsoleColor.Red, "소지금이 부족합니다! 슬롯 머신을 돌릴 수 없습니다."); 

                Console.SetCursorPosition(0, 0);
                return new string[] { "❌", "❌", "❌" };
            }
        }

        private void Resultprint(string[] result) // 출력 UI
        {
            // 결과 출력
            Player player = GameManager.player;

            Print.ColorPrintScreen(ConsoleColor.Yellow, $"현재 소지금 : {player.playerGold} Gold\n"); // 1번째 줄 

            Console.WriteLine("\n----- 슬롯 머신 ------"); //4번째 줄

            Console.WriteLine("   |    |    |    |"); // 임시 5번째 줄

            Console.WriteLine("----------------------\n"); // 6번째 줄

            Console.SetCursorPosition(0, 4);
            Thread.Sleep(500);
            Console.Write($"   | {result[0]} | "); // 5번째 줄 

            Thread.Sleep(500);
            Console.Write($"{result[1]} | "); // 5번째 줄 

            Thread.Sleep(500);
            Console.WriteLine($"{result[2]} |");  // 5번째 줄 

            Console.SetCursorPosition(0, 8); // 줄 이동
        }

        private void GamblingResult(string[] result) // 게임 결과
        {
            if (result[0] == "❌" || result[1] == "❌" || result[2] == "❌") // 소지금 부족시 "❌" 이모지 읽히는 문제 감지
            {
                return;
            }

            if (result[0] == result[1] && result[1] == result[2])
            {
                if (result[0] == "7️")
                {
                    Console.WriteLine("잭팟! 배팅금의 10배를 획득했습니다!");

                    GameManager.player.playerGold += 5000;
                }
                else
                {
                    Console.WriteLine("축하합니다! 배팅금의 5배를 획득하셨습니다.");

                    GameManager.player.playerGold += 2500;
                }
            }
            else
            {
                Console.WriteLine("다음 기회를 노려주세요");
            }
        }
    }
}


```

DungeonScene 회피와 치명타 기능 추가, 및 마무리

GamblingScene 추가, 슬롯머신 도박기능 추가 및 버그 수정

using System.Text; // UTP-8 이모지 때문에 사용 
ㄴ 이 구문 유용하게 사용했습니다.

</details>

<details>
<summary>2024.10.04 </summary>

마지막 제출을 앞두고 Text Rpg 의 수치조정(밸런스 조정)을 진행했습니다.

기존에 추가되어있던 몹 2종류를 던전에서 실질적으로 등장하게 수정했고, 

플레이어의 기본 스탯 및 몹의 정보를 수정했습니다.


```C
몹 수정 부분 중 1

private (int Health, int Attack, int Defence, int exp) GetStatsByLevel(int level)
{
    switch (level)
    {
        case 1:
            return (60, 25, 5, 4);
        case 2:
            return (90, 35, 10, 6);
        case 3:
            return (160, 45, 15, 8);
        case 4:
            return (190, 55, 20, 10);
        default:
            return (0, 0, 0, 0); // 유효하지 않은 레벨의 경우 기본값
    }
}

Hp값, 공격력, 방어력, 플레이어 획득 경험치량


플레이어 수정 부분

 switch (keyInfo.Key)
 {
     case ConsoleKey.D1:
         ShowJobDetails("전사", 30, 50, 700, 150, 3000);
         GameManager.player = new Player(playerName, "전사", 30, 50, 700, 150, 50, 3000);
         break;
     case ConsoleKey.D2:
         ShowJobDetails("궁수", 50, 30, 500, 120, 3000);
         GameManager.player = new Player(playerName, "궁수", 50, 30, 500, 120, 50, 3000);
         break;
     case ConsoleKey.D3:
         ShowJobDetails("마법사", 40, 30, 500, 200, 3000);
         GameManager.player = new Player(playerName, "마법사", 40, 30, 500, 200, 50, 3000);
         break;
     case ConsoleKey.D4:
         ShowJobDetails("도적", 60, 20, 600, 150, 3000);
         GameManager.player = new Player(playerName, "도적", 60, 20, 600, 150, 50, 3000);
         break;
     default:
         Console.WriteLine("잘못된 선택입니다. 다시 입력해주세요.");
         Thread.Sleep(500);
         break;
 }

player 이름, 직업명, 공격력, 방어력, 체력, 마나, 레벨업 경험치요구량, 초기 골드

```

일주일간 다들 고생많으셨습니다!


</details>

<details>
<summary>2024.10.07 </summary>

개인과제 주입니다.
기존 zep 에서 보이는 거 처럼 캐릭터를 조작하고, 여러 ui들을 띄우는 것을 unity로 구현하는 과제입니다.

```C
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class CameraMove : MonoBehaviour
{
    public Transform target;

    public float smoothSpeed = 3;
    public Vector2 offset;
    public float limitMinX, limitMaxX, limitMinY, limitMaxY;
    float cameraHalfWidth, cameraHalfHeight;

    void Start()
    {
        cameraHalfWidth = Camera.main.aspect * Camera.main.orthographicSize;
        cameraHalfHeight = Camera.main.orthographicSize;
    }

    private void LateUpdate()
    {
        Vector3 desiredPosition = new Vector3(
           Mathf.Clamp(target.position.x + offset.x, limitMinX + cameraHalfWidth, limitMaxX - cameraHalfWidth),   
           Mathf.Clamp(target.position.y + offset.y, limitMinY + cameraHalfHeight, limitMaxY - cameraHalfHeight), -10);                                                                                                  
        transform.position = Vector3.Lerp(transform.position, desiredPosition, Time.deltaTime * smoothSpeed);
    }
}

```
현재 기본 뼈대를 잡고 플레이어를 따라다니는 카메라 시점까지 구현했고 내일 추가로 ui 쪽을 작업할 예정입니다.

</details>

<details>
<summary>2024.10.08 </summary>

```c
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class PlayerMove : MonoBehaviour
{

    public float moveSpeed = 3.0f;
    Vector2 movement = new Vector2();
    Rigidbody2D rigidbody2D;

    Animator animator;
    string animationsState = "AnimationState";

    enum States
    {
        right = 1,
        left = 2,
        down = 3,
        up = 4,
        idle = 5
    }
    void Start()
    {
        animator = GetComponent<Animator>();
        rigidbody2D = GetComponent<Rigidbody2D>();
    }
    void Update()
    {
        UpdateState();
    }

    private void FixedUpdate()
    {
        MoveCharacter();
    }

    private void MoveCharacter()
    {
        movement.x = Input.GetAxisRaw("Horizontal");
        movement.y = Input.GetAxisRaw("Vertical");

        movement.Normalize();

        rigidbody2D.velocity = movement * moveSpeed;
    }

    private void UpdateState()
    {
        if (movement.x > 0)
        {
            animator.SetInteger(animationsState, (int)States.right);
        }
        else if (movement.x < 0)
        {
            animator.SetInteger(animationsState, (int)States.left);
        }
        else if (movement.y > 0)
        {
            animator.SetInteger(animationsState, (int)States.up);
        }
        else if (movement.y < 0)
        {
            animator.SetInteger(animationsState, (int)States.down);
        }
        else
        {
            animator.SetInteger(animationsState, (int)States.idle);
        }
    }
}


```
캐릭터의 기본 이동로직 구현 , 타일셋을 구성하고 콜라이더를 넣어서 벽과의 충돌을 방지하는 것을 구현했습니다. 목요일 ui 등을 추가 할 예정입니다.

</details>
