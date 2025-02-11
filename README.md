<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# BTP Experience 2025

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Links

### Link para acessar o Integration Suite:

https://sap-btp-experience-is-shared-instances-ag2uetcp.integrationsuite.cfapps.us10-002.hana.ondemand.com/shell/home

Login: intelligenzait_X@sap.com (sendo X, número de 1 a 40)

Senha: @Welcome01

### STEP 3 - Exemplos:

/bestrun/RatedPartner?$top=10&$expand=location&$select=name,rating

/bestrun/RatedPartner?$top=30&$filter=rating/Moodys eq 'AAB'

### STEP 5:

<b>Token</b>

curl -X POST https://sap-btp-experience-is-shared-instances-ag2uetcp.authentication.us10.hana.ondemand.com/oauth/token -H "Content-Type:application/x-www-form-urlencoded" -d "grant_type=client_credentials" -d "client_id=sb-b0fe245d-8735-407d-8adc-07c7b067feac!b262215|sap-graph!b79797" -d "client_secret=d396f1a4-be0b-40a3-98cd-fcf797253de8$lwBTl2jy3gbwaAiEcGNtpVHBaugQ7Zp5KY0njcYG2pU="

 

<b>Requisitando seu Proxy</b>

curl -X GET https://u311.test.apimanagement.us10.hana.ondemand.com/<SEU_PROXY>/RatedPartner?$top=1 -H "Authorization: Bearer <TOKEN >"

 

### STEP 6


<b>Informações para Police</b>

<b>Client ID:</b> sb-b0fe245d-8735-407d-8adc-07c7b067feac!b262215|sap-graph!b79797

<b>Client Secret:</b> d396f1a4-be0b-40a3-98cd-fcf797253de8$lwBTl2jy3gbwaAiEcGNtpVHBaugQ7Zp5KY0njcYG2pU=

<b>URL:</b> https://sap-btp-experience-is-shared-instances-ag2uetcp.authentication.us10.hana.ondemand.com/oauth/token

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'github-pages',
  owner: '@me',
  name: 'skills-github-pages',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

<footer>


<b>Link do exercício:</b>

https://github.com/SAP-samples/teched2023-IN267/blob/main/exercise/README.md
<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

</footer>
