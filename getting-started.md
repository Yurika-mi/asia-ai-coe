# 샌드박스 시작하기

## Azure Portal에 로그인

1. 새 브라우저 탭을 사용하여 [Azure Portal](https://portal.azure.com)로 이동합니다.
   
1. **[Microsoft Azure에 로그인]** 탭에서 로그인 화면이 표시됩니다. 아래 이메일/사용자 이름을 입력한 후 **[다음]** 을 클릭합니다.

   * 이메일/사용자 이름: <inject key="AzureAdUserEmail"></inject>
   
     ![](media/image7.png "Enter Email")

     > **참고:** **[Microsoft Edge 모바일 앱 다운로드]** 팝업이 표시되면 **[표시 안 함]** 드롭다운을 클릭하고 **[이 권장 사항을 다시 표시하지 않음]** 을 선택합니다.
     
1. 아래 비밀번호를 입력하고 **[로그인]** 을 클릭합니다.

   * 비밀번호: <inject key="AzureAdUserPassword"></inject>
   
     ![](media/Sign-in-page.png "Enter Password")
  
1. **[로그인 상태를 유지하시겠습니까?]** 팝업이 표시되면 **[아니오]** 를 클릭합니다.

1. **[무료 Azure Advisor 권장 사항이 있습니다!]** 팝업이 표시되면 창을 닫고 랩을 계속 진행합니다.

1. **[Microsoft Azure 시작]** 팝업 창이 표시되면 **[나중에]** 를 클릭하여 둘러보기를 건너뜁니다.

## GitHub에 로그인

1. 브라우저를 열고 (InPrivate/시크릿 창 권장) 아래 단계에 따라 GitHub 계정을 활성화합니다.

1. 아래 URL로 이동하여 초대를 수락합니다.

   - **InviteRedirectURL:** `https://myapplications.microsoft.com/?tenantid=f871d17e-efcd-44c7-ba5a-0162efa2fded`

1. **[로그인]** 탭이 표시됩니다. 아래 자격 증명을 입력합니다.
 
   - **이메일/사용자 이름:** **<inject key="AzureAdUserEmail"></inject>**
 
       ![Enter Your Username](./media3/login1.png)

1. 다음으로 비밀번호를 입력하여 로그인합니다.
 
   - **비밀번호:** **<inject key="AzureAdUserPassword"></inject>**
 
      ![Enter Your Password](./media3/login2.png)

1. 다음 창에서 **[수락]** 을 클릭하여 초대를 승인합니다.

1. **[로그인 상태를 유지하시겠습니까?]** 팝업이 표시되면 **[아니오]** 를 클릭합니다.

1. 완료되면 이 브라우저 탭을 닫고 아래 URL을 사용하여 새 브라우저 탭에서 GitHub 로그인 페이지로 이동합니다.

   ```
   https://github.com/login
   ```

1. **[GitHub에 로그인]** 탭에서 로그인 화면이 표시됩니다. 제공된 GitHub 사용자 이름을 입력한 후 **[ID 공급자로 로그인]** 을 클릭하여 계속 진행합니다 **(2)**.

   - GitHub 사용자: 

    ```
    odl-user-<inject key="Deployment ID" enableCopy="false"/>_clabs
    ```

    ![](./media3/github-logina.png)

1. **[CloudLabs Organizations 싱글 사인온]** 페이지에서 **[계속]** 을 클릭합니다.

   ![](./media3/github-loginb.png)

1. 로그인을 요청받으면 환경에서 제공된 이메일 및 비밀번호로 로그인합니다.

   - **이메일/사용자 이름:** **<inject key="AzureAdUserEmail"></inject>**

   - **비밀번호:** **<inject key="AzureAdUserPassword"></inject>**

1. GitHub 로그인이 완료되었습니다.


수고하셨습니다! 이제 시작할 준비가 되었습니다!
