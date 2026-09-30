EXERCISE 8-1
1. 구조
2. 상호작용
3. 구조
4. 행위
5. 상호작용
6. 행위

EXERCISE 8-2
1. "주문을 생성한다" ┈«include»┈> "판매상태를 확인한다"
2. "게시글을 찜한다" ┈«extend»┈> "게시글을 열람한다"
3. "거래 후기를 작성한다" ┈«extend»┈> "거래를 확정한다"
4. "게시글을 등록/수정한다" ┈«include»┈> "금칙어를 검사한다"
5. "회원" ┈«include»┈> "구매자" "판매자"

EXERCISE 8-3
1. Member ───────── Post
   연관 / 1 : 0..*

2. Post ◆──────── PostImage
   합성 / 1 : 0..*

3. Buyer ──────▷ Member
   일반화 

4. Transaction ┈┈────▶ PaymentMethod
   의존 / 1 : 1

5. Club ◇──────── Student
   집합 / 1 : *