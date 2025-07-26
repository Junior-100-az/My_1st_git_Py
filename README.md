# My_1st_git_Py
ans_dict = {
      0: 88.4,
      1: 223.1,
      2: 65.4


}

pro_dict = {
    0: "0번 문제 발문",
    1: "1번 문제 발문",
    2: "2번 문제 발문"


}

#일단 기능 구현은 성공했고, 추후에 좀 더 다듬어 봐야겠다.
class ProblemSolving:
    
      
    def __init__(self):
        pass
       
    def True_Or_False(self):
        for i in range(0, 3):
                print(pro_dict[i])#pro_dict라는 첫 key가 0부터 시작하는 딕셔너리 존재 가정
                ans = float(input("정답을 입력하십시오."))
                if ans_dict[i] == ans:    #self.num은 정답 값, num은 입력 받은 값
                    print("정답입니다! 기억 회복 + 0.3%")
                else:
                    print("오답입니다. 다시 도전하십시오.")
                if i == 2:
                    print("모든 문제를 푸셨습니다.\n업적달성:100%생과일..아니 데이터 과학자!")
                    break

        
            

pro_mean = ProblemSolving()


pro_mean.True_Or_False()
