# Getting Started

1. [Fork](https://github.com/morethanmin/morethan-log/fork) the repo to your Profile.
2. Duplicate [this Notion template](https://quasar-season-ed5.notion.site/12c38b5f459d4eb9a759f92fba6cea36?v=2e7962408e3842b2a1a801bf3546edda), and Share to Web.
3. Copy the Web Link and keep note of the Notion Page Id from the Link which will be in this format [username.notion.site/`NOTION_PAGE_ID`?v=`VERSION_ID`]. 
4. Clone your forked repo and then customize `site.config.js` based on your preference.
5. Deploy on Vercel, with the following environment variables.

   - `NOTION_PAGE_ID` (Required): The Notion page Id got from the Share to Web URL. This is not the entire URL, but just the NOTION_PAGE_ID part as shown above.
   - `NEXT_PUBLIC_GOOGLE_MEASUREMENT_ID` : For Google analytics Plugin.
   - `NEXT_PUBLIC_GOOGLE_SITE_VERIFICATION` : For Google search console Plugin.
   - `NEXT_PUBLIC_NAVER_SITE_VERIFICATION` : For Naver search advisor Plugin.
