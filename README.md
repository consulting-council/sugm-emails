# sugm-emails

Marketing team emails for Seattle Union Gospel Mission

## Definitions

- codes: Represents the id number for the email and associated campain. ex: `L23F1EAP`

## Email Components
### Copy Paragraph

Use the snippet example below to add copy paragraphs to the email. Each paragraph should be wrapped by the snipped to provide styles and table structure.

```
<tr>
    <td
        style="
            font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif;
            font-size: 20px;
            line-height: 30px;
            font-weight: normal;
            color: #000000;
            padding-left: 30px;
            padding-right: 30px;
            padding-bottom: 20px;
            "
            align="left">
                Over the last few months, the Mission has been working to create
                new content to share with those who live in the greater Seattle
                area...
    </td>
</tr>
```

### Inline Links

Use the snipped below to create a link in the copy. The brand styles are managed via the `a` tag. Change the href link to update the link target. Link text should be wrapped with a span tag found below. Inline links must be wrapped with a paragraph snipped in the example above.

```
<a
style="color: #f15a29; text-decoration: underline"
href="https://www.ugm.org/changed-lives/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
    <span style="color: #f15a29; text-decoration: underline">
        help the lost become found
    </span>
</a>
```

### Images

Use the image snipped below to include in-line images. Update the src url, and the href location to use the intended image and link target location.

```
 <tr>
    <td
    style="
        font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif;
        font-size: 20px;
        line-height: 30px;
        font-weight: normal;
        color: #000000;
        padding-left: 30px;
        padding-right: 30px;
        padding-bottom: 20px;
    "
    align="left">
        <a
            style="color: #f15a29; text-decoration: underline"
            href="https://www.ugm.org/changed-lives/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
            <img
            class="big"
            style="
                display: block;
                height: auto;
                border: 0;
                width: 575px;
                max-width: 100%;
            "
            title="Behind the scenes"
            src="http://www.myugm.org/images/content/pagebuilder/July_sustainer_email_2.png"
            alt="Family photo shoot behind the scenes"
            width="600" />
        </a>
    </td>
</tr>
```

### Section Headers

Use the snippet below to create a section header. Use all caps when updating the section copy.

```
<tr>
    <td style="font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; font-size: 20px; line-height: 30px; font-weight: normal; color: #ffffff; padding-left: 30px; padding-right: 30px; padding-bottom: 20px; padding-top: 20px; background-color: #58595b; vertical-align: middle;" align="left">
        <strong>CHURCH SPOTLIGHT</strong>
    </td>
</tr>
```

### Footer
The footer is composed of SUGM branding, bible verse, and social links. Update the bible verse, and link codes in the href targets.

```
<!--Footer Table-->
<tr>
    <td align="center">
    <table
        class="w100"
        style="width: 575px"
        border="0"
        cellspacing="0"
        cellpadding="0"
        align="center">
        <tbody>
        <tr>
            <td
            style="padding-top: 30px; padding-bottom: 30px"
            align="center">
            <a
                style="display: inline-block"
                href="https://www.ugm.org/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E01Z&amp;utm_content=where-needed-most_nil_nil_nil&amp;s_subsrc=L23G3EAPC1E01Z&amp;mwsc=SUGM-325-L23G3EAPC1E01Z">
                <img
                style="display: block; border: none; max-width: 115px"
                src="http://www.myugm.org/images/content/pagebuilder/mission-iconicsignlogo-color-125px_1.png"
                alt="Seattle's Union Gospel Mission Logo"
                width="115"
                height="60" />
            </a>
            </td>
        </tr>
        <tr>
            <td
            style="
                font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                font-size: 14px;
                line-height: 24px;
                font-weight: normal;
                color: #555;
                font-style: italic;
                padding-left: 30px;
                padding-right: 30px;
            "
            align="center">
            &ldquo;Blessed is the one who perseveres under trial because,
            having stood the test, that person will receive the crown of
            life that the Lord has promised to those who love him.&rdquo;
            </td>
        </tr>
        <tr>
            <td
            style="
                font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                font-size: 13px;
                line-height: 23px;
                font-weight: bold;
                color: #555;
                padding-left: 30px;
                padding-right: 30px;
                padding-bottom: 30px;
            "
            align="center">
            James 1:12 NIV
            </td>
        </tr>
        <tr>
            <td
            style="
                font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                font-size: 12px;
                line-height: 22px;
                font-weight: normal;
                color: #555;
                padding-left: 30px;
                padding-right: 30px;
            "
            align="center">
            Seattle&rsquo;s Union Gospel Mission
            </td>
        </tr>
        <tr>
            <td
            style="
                font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                font-size: 12px;
                line-height: 22px;
                font-weight: normal;
                color: #555;
                padding-left: 30px;
                padding-right: 30px;
            "
            align="center">
            3800 S Othello St, Seattle, WA 98118
            </td>
        </tr>
        <tr>
            <td
            style="
                font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                font-size: 12px;
                line-height: 22px;
                font-weight: normal;
                color: #555;
                padding-left: 30px;
                padding-right: 30px;
                padding-bottom: 20px;
            "
            align="center">
            <a
                style="text-decoration: underline; color: #555"
                rel="noopener"
                href="http://www.myugm.org/site/CO"
                target="_blank">
                Manage my subscription
            </a>
            &nbsp;&nbsp;|&nbsp;
            <a
                style="text-decoration: underline; color: #555"
                rel="noopener"
                href="https://www.myugm.org/site/SPageServer/?pagename=donate_responsive_evergreen&amp;utm_source=convio&amp;utm_medium=email&amp;utm_campaign=MW_SUGM_329-46305_sustainer_220221214__L23G3EAP&amp;utm_content=recurring_nil_nil_nil&amp;s_subsrc=L23G3EAP&amp;mwsc=SUGM-329-L23G3EAP"
                target="_blank">
                Donate Now
            </a>
            </td>
        </tr>
        <!--Social Links-->
        <tr>
            <td style="padding-bottom: 20px" align="center">
            <table
                style="width: 100px"
                border="0"
                cellspacing="0"
                cellpadding="0"
                align="center">
                <tbody>
                <tr>
                    <td style="padding: 0 0 0 0px; border: 0">
                    <a
                        style="
                        -ms-text-size-adjust: 100%;
                        -webkit-text-size-adjust: 100%;
                        text-decoration: none;
                        "
                        href="https://www.facebook.com/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                        <img
                        style="
                            outline: none;
                            text-decoration: none;
                            -ms-interpolation-mode: bicubic;
                            border: 0;
                            display: block;
                        "
                        src="http://www.myugm.org/images/content/pagebuilder/Facebook_1.png"
                        alt="FB"
                        width="25"
                        height="25" />
                    </a>
                    </td>
                    <td style="padding: 0 0 0 10px; border: 0">
                    <a
                        style="
                        -ms-text-size-adjust: 100%;
                        -webkit-text-size-adjust: 100%;
                        text-decoration: none;
                        "
                        href="https://www.instagram.com/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                        <img
                        style="
                            outline: none;
                            text-decoration: none;
                            -ms-interpolation-mode: bicubic;
                            border: 0;
                            display: block;
                        "
                        src="http://www.myugm.org/images/content/pagebuilder/Instagram_2.png"
                        alt="IG"
                        width="25"
                        height="25" />
                    </a>
                    </td>
                    <td style="padding: 0 0 0 10px; border: 0">
                    <a
                        style="
                        -ms-text-size-adjust: 100%;
                        -webkit-text-size-adjust: 100%;
                        text-decoration: none;
                        "
                        href="https://twitter.com/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                        <img
                        style="
                            outline: none;
                            text-decoration: none;
                            -ms-interpolation-mode: bicubic;
                            border: 0;
                            display: block;
                        "
                        src="http://www.myugm.org/images/content/pagebuilder/Twitter_1.png"
                        alt="TW"
                        width="25"
                        height="25" />
                    </a>
                    </td>
                    <td style="padding: 0 0 0 10px">
                    <a
                        style="
                        -ms-text-size-adjust: 100%;
                        -webkit-text-size-adjust: 100%;
                        text-decoration: none;
                        "
                        href="https://www.youtube.com/user/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                        <img
                        style="
                            outline: none;
                            text-decoration: none;
                            -ms-interpolation-mode: bicubic;
                            border: 0;
                            display: block;
                        "
                        src="http://www.myugm.org/images/content/pagebuilder/YouTube_1.png"
                        alt="YT"
                        width="25"
                        height="25" />
                    </a>
                    </td>
                </tr>
                </tbody>
            </table>
            </td>
        </tr>
        <!--End Social Links-->
        </tbody>
    </table>
    </td>
</tr>
```
### Outlines and Wrappers

#### Email Container Wrapper
This wrapper is to wrap all content. This snippet also includes all meta data and default styles. The components should be added within the `<tbody>` tag. This wrapper also includes the preview text, update this copy as defined in the requirements (see `<!--Preview Text-->`).

```
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta name="color-scheme" content="light" />
<meta name="supported-color-schemes" content="light" />
<!--Main Styles-->
<style type="text/css">
  <!--
    	      p {
    	        display: none !important;
    	      }
    	      #cv-poweredBy {
    	        display: none !important;
    	      }

    	      p {
    	        display: none !important;
    	      }
    	      #cv-poweredBy {
    	        display: none !important;
    	      }
    	      * {
    	        -webkit-text-size-adjust: none;
    	      }
    	      body {
    	        margin: 0 !important;
    	        padding: 0 !important;
    	      }
    	      body,
    	      table,
    	      td,
    	      p,
    	      a {
    	        -ms-text-size-adjust: 100% !important;
    	        -webkit-text-size-adjust: 100% !important;
    	      }
    	      table,
    	      td {
    	        border-spacing: 0 !important;
    	        mso-table-lspace: 0px !important;
    	        mso-table-rspace: 0pt !important;
    	        border-collapse: collapse !important;
    	      }
    	      .ExternalClass * {
    	        line-height: 100%;
    	      }
    	      .mobile-link a,
    	      .mobile-link span {
    	        text-decoration: none !important;
    	        color: inherit !important;
    	        border: none !important;
    	      }

    	      @media only screen and (max-width: 575px) {
    	        body {
    	          min-width: 320px;
    	          margin: 0;
    	        }
    	        .hide-m {
    	          display: none !important;
    	        }
    	        .show-for-small {
    	          display: block !important;
    	          overflow: visible !important;
    	          width: auto !important;
    	          max-height: inherit !important;
    	        }
    	        .no-float {
    	          float: none !important;
    	        }
    	        .block {
    	          display: block !important;
    	        }
    	        .resize-image {
    	          width: 100%;
    	          height: auto;
    	        }
    	        .center-image {
    	          display: block;
    	          margin: 0 auto;
    	        }

    	        .text-center {
    	          text-align: center !important;
    	        }
    	        .font-14 {
    	          font-size: 14px !important;
    	          line-height: 16px !important;
    	        }
    	        .font-16 {
    	          font-size: 16px !important;
    	          line-height: 18px !important;
    	        }
    	        .font-18 {
    	          font-size: 18px !important;
    	          line-height: 20px !important;
    	        }
    	        .font-20 {
    	          font-size: 20px !important;
    	          line-height: 22px !important;
    	        }
    	        .font-22 {
    	          font-size: 22px !important;
    	          line-height: 24px !important;
    	        }

    	        .pad-t-0 {
    	          padding-top: 0px !important;
    	        }
    	        .pad-r-0 {
    	          padding-right: 0px !important;
    	        }
    	        .pad-b-0 {
    	          padding-bottom: 0px !important;
    	        }
    	        .pad-l-0 {
    	          padding-left: 0px !important;
    	        }
    	        .pad-t-20 {
    	          padding-top: 20px !important;
    	        }
    	        .pad-r-20 {
    	          padding-right: 20px !important;
    	        }
    	        .pad-b-20 {
    	          padding-bottom: 20px !important;
    	        }
    	        .pad-l-20 {
    	          padding-left: 20px !important;
    	        }
    	        .pad-0 {
    	          padding-top: 0px !important;
    	          padding-right: 0px !important;
    	          padding-bottom: 0px !important;
    	          padding-left: 0px !important;
    	        }
    	        .pad-10 {
    	          padding-top: 10px !important;
    	          padding-right: 10px !important;
    	          padding-bottom: 10px !important;
    	          padding-left: 10px !important;
    	        }
    	        .pad-20 {
    	          padding-top: 20px !important;
    	          padding-right: 20px !important;
    	          padding-bottom: 20px !important;
    	          padding-left: 20px !important;
    	        }
    	        .pad-sides-0 {
    	          padding-right: 0px !important;
    	          padding-left: 0px !important;
    	        }
    	        .pad-sides-10 {
    	          padding-right: 10px !important;
    	          padding-left: 10px !important;
    	        }
    	        .pad-sides-20 {
    	          padding-right: 20px !important;
    	          padding-left: 20px !important;
    	        }

    	        .w100 {
    	          width: 100% !important;
    	          min-width: initial !important;
    	        }
    	        .w90 {
    	          width: 90% !important;
    	          min-width: initial !important;
    	        }
    	        .w50 {
    	          width: 50% !important;
    	          min-width: initial !important;
    	        }
    	      }
  -->
</style>
<p
  style="
    display: none;
    width: 0px;
    height: 0px;
    max-height: 0px;
    mso-hide: all;
    margin: 0px;
  ">
  <!-- PREVIEW TEXT -->
  A peak into this coming year &gt;&gt
</p>

<table
  style="width: 100%; background-color: #eeece7"
  border="0"
  cellspacing="0"
  cellpadding="0"
  align="center"
  bgcolor="#eeece7">
  <tbody>
    <td align="center">
      <table
            class="w100"
            style="width: 575px"
            border="0"
            cellspacing="0"
            cellpadding="0"
            align="center">
            <tbody>
              <tr>
                <td
                  class="pad-sides-20"
                  style="
                    font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                    font-size: 13px;
                    line-height: 23px;
                    font-weight: bold;
                    color: #393d47;
                    padding-top: 30px;
                    padding-bottom: 10px;
                    padding-right: 20px;
                  "
                  align="right">
                  SEATTLE&rsquo;S UNION GOSPEL MISSION
                </td>
              </tr>
                <tr>
                <td align="center">&nbsp;</td>
                </tr>
            </tbody>
          </table>
        <!--Add Main Content Wrapper and Components Here-->
        <!--Add Footer Content Wrapper and Components Here-->
    </td>
  </tbody>
</table>
<style type="text/css" data-ignore-inlining="">
  <!--
    	      @media (prefers-color-scheme: dark) {
    	        #_t::before {
    	          content: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?rd&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	        }
    	      }
    	      @media (prefers-color-scheme: light) {
    	        #_t::before {
    	          content: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?rl&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	        }
    	      }
    	      @media print {
    	        #_t {
    	          background-image: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?p&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	        }
    	      }
  -->
</style>
<style type="text/css">
  <!--
    	      div.OutlookMessageHeader {
    	        background-image: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?f&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	      }
    	      table.moz-email-headers-table {
    	        background-image: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?f&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	      }
    	      blockquote #_t {
    	        background-image: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?f&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	      }
    	      #MailContainerBody #_t {
    	        background-image: url("https://3av6ouqk.emltrk.com/v2/3av6ouqk?f&i=[[S1:cons_id]]&t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&utm_content=where-needed-most_nil_nil_nil");
    	      }
  -->
</style>
<div id="_t">&nbsp;</div>
<img
  src="https://3av6ouqk.emltrk.com/v2/3av6ouqk?i=[[S1:cons_id]]&amp;t=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E0Z&amp;utm_content=where-needed-most_nil_nil_nil"
  border="0"
  alt=""
  width="1"
  height="1" />

```

#### Main Content Wrapper
This wrapper includes SUGM branding and logos. Add this wrapper in the email container wrapper section degined above. The main sections in wrapper include the introduction and or welcom section and the main copy sections. Copy, section headers, images, and links are to be included in the main acopy section. Be sure to refer to the component snippets listed above.


```
<tr>
  <td align="center">
    <table
      class="w100"
      style="width: 575px; background-color: #ffffff"
      border="0"
      cellspacing="0"
      cellpadding="0"
      align="center">
      <tbody>
        <tr>
          <td
            style="
              font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif;
              font-size: 20px;
              line-height: 30px;
              font-weight: normal;
              color: #000000;
              padding-left: 30px;
              padding-right: 30px;
              padding-bottom: 20px;
              padding-top: 20px;
            "
            align="left">
            Hi [[?xx::x[[S1:first_name]]x::Friend::[[S1:first_name]]]],
          </td>
        </tr>
        <!--Add Email Components Here-->
      </tbody>
    </table>
  </td>
</tr>
```

#### Footer Wrapper
The footer contains SUGM branding logos, social links, bible verses, and account management links. 

```
<tr>
    <td align="center">
        <table
          class="w100"
          style="width: 575px"
          border="0"
          cellspacing="0"
          cellpadding="0"
          align="center">
            <tbody>
                <tr>
                    <td
                        style="padding-top: 30px; padding-bottom: 30px"
                        align="center">
                        <a
                        style="display: inline-block"
                        href="https://www.ugm.org/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=MW_SUGM_325-46519_easter_20230314_1_L23G3EAPC1E01Z&amp;utm_content=where-needed-most_nil_nil_nil&amp;s_subsrc=L23G3EAPC1E01Z&amp;mwsc=SUGM-325-L23G3EAPC1E01Z">
                            <img
                                style="display: block; border: none; max-width: 115px"
                                src="http://www.myugm.org/images/content/pagebuilder/mission-iconicsignlogo-color-125px_1.png"
                                alt="Seattle's Union Gospel Mission Logo"
                                width="115"
                                height="60" />
                        </a>
                    </td>
             </tr>
                <tr>
                    <td
                        style="
                        font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                        font-size: 14px;
                        line-height: 24px;
                        font-weight: normal;
                        color: #555;
                        font-style: italic;
                        padding-left: 30px;
                        padding-right: 30px;
                        "
                        align="center">
                        &ldquo;Blessed is the one who perseveres under trial because,
                        having stood the test, that person will receive the crown of
                        life that the Lord has promised to those who love him.&rdquo;
                    </td>
                </tr>
            <tr>
              <td
                style="
                  font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                  font-size: 13px;
                  line-height: 23px;
                  font-weight: bold;
                  color: #555;
                  padding-left: 30px;
                  padding-right: 30px;
                  padding-bottom: 30px;
                "
                align="center">
                    James 1:12 NIV
                </td>
            </tr>
            <tr>
              <td
                style="
                  font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                  font-size: 12px;
                  line-height: 22px;
                  font-weight: normal;
                  color: #555;
                  padding-left: 30px;
                  padding-right: 30px;
                "
                align="center">
                Seattle&rsquo;s Union Gospel Mission
              </td>
            </tr>
            <tr>
              <td
                style="
                  font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                  font-size: 12px;
                  line-height: 22px;
                  font-weight: normal;
                  color: #555;
                  padding-left: 30px;
                  padding-right: 30px;
                "
                align="center">
                3800 S Othello St, Seattle, WA 98118
              </td>
            </tr>
            <tr>
              <td
                style="
                  font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
                  font-size: 12px;
                  line-height: 22px;
                  font-weight: normal;
                  color: #555;
                  padding-left: 30px;
                  padding-right: 30px;
                  padding-bottom: 20px;
                "
                align="center">
                <a
                  style="text-decoration: underline; color: #555"
                  rel="noopener"
                  href="http://www.myugm.org/site/CO"
                  target="_blank">
                  Manage my subscription
                </a>
                &nbsp;&nbsp;|&nbsp;
                <a
                  style="text-decoration: underline; color: #555"
                  rel="noopener"
                  href="https://www.myugm.org/site/SPageServer/?pagename=donate_responsive_evergreen&amp;utm_source=convio&amp;utm_medium=email&amp;utm_campaign=MW_SUGM_329-46305_sustainer_220221214__L23G3EAP&amp;utm_content=recurring_nil_nil_nil&amp;s_subsrc=L23G3EAP&amp;mwsc=SUGM-329-L23G3EAP"
                  target="_blank">
                  Donate Now
                </a>
              </td>
            </tr>
            <!--Social Links-->
            <tr>
              <td style="padding-bottom: 20px" align="center">
                <table
                  style="width: 100px"
                  border="0"
                  cellspacing="0"
                  cellpadding="0"
                  align="center">
                  <tbody>
                    <tr>
                      <td style="padding: 0 0 0 0px; border: 0">
                        <a
                          style="
                            -ms-text-size-adjust: 100%;
                            -webkit-text-size-adjust: 100%;
                            text-decoration: none;
                          "
                          href="https://www.facebook.com/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                          <img
                            style="
                              outline: none;
                              text-decoration: none;
                              -ms-interpolation-mode: bicubic;
                              border: 0;
                              display: block;
                            "
                            src="http://www.myugm.org/images/content/pagebuilder/Facebook_1.png"
                            alt="FB"
                            width="25"
                            height="25" />
                        </a>
                      </td>
                      <td style="padding: 0 0 0 10px; border: 0">
                        <a
                          style="
                            -ms-text-size-adjust: 100%;
                            -webkit-text-size-adjust: 100%;
                            text-decoration: none;
                          "
                          href="https://www.instagram.com/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                          <img
                            style="
                              outline: none;
                              text-decoration: none;
                              -ms-interpolation-mode: bicubic;
                              border: 0;
                              display: block;
                            "
                            src="http://www.myugm.org/images/content/pagebuilder/Instagram_2.png"
                            alt="IG"
                            width="25"
                            height="25" />
                        </a>
                      </td>
                      <td style="padding: 0 0 0 10px; border: 0">
                        <a
                          style="
                            -ms-text-size-adjust: 100%;
                            -webkit-text-size-adjust: 100%;
                            text-decoration: none;
                          "
                          href="https://twitter.com/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                          <img
                            style="
                              outline: none;
                              text-decoration: none;
                              -ms-interpolation-mode: bicubic;
                              border: 0;
                              display: block;
                            "
                            src="http://www.myugm.org/images/content/pagebuilder/Twitter_1.png"
                            alt="TW"
                            width="25"
                            height="25" />
                        </a>
                      </td>
                      <td style="padding: 0 0 0 10px">
                        <a
                          style="
                            -ms-text-size-adjust: 100%;
                            -webkit-text-size-adjust: 100%;
                            text-decoration: none;
                          "
                          href="https://www.youtube.com/user/SeattlesUGM/?utm_source=convio&amp;utm_medium=email&amp;utm_campaign=L23G3EAPF2EAP&amp;utm_content=sustainer-engagement&amp;s_subsrc=L23G3EAPF2EAP">
                          <img
                            style="
                              outline: none;
                              text-decoration: none;
                              -ms-interpolation-mode: bicubic;
                              border: 0;
                              display: block;
                            "
                            src="http://www.myugm.org/images/content/pagebuilder/YouTube_1.png"
                            alt="YT"
                            width="25"
                            height="25" />
                        </a>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </td>
            </tr>
            <!--End Social Links-->
          </tbody>
        </table>
    </td>
</tr>
```