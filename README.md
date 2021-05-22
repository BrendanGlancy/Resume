<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns:doc="http://xsltsl.org/xsl/documentation/1.0" xmlns:dt="http://xsltsl.org/date-time" xmlns:str="http://xsltsl.org/string" xmlns:msxsl="urn:schemas-microsoft-com:xslt">
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-16" />
    <title>BrendanGlancy</title>
    <style type="text/css" id="font">
        @import url("https://fonts.googleapis.com/css?family=Hind:300,400,500,700");
    </style>
    <style type="text/css" id="static">
        html,body{margin:0;border:0;outline:0;vertical-align:baseline;background:transparent}
        span,applet,object,iframe,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td{margin:0;padding:0;border:0;outline:0;font-size:100%;vertical-align:baseline;background:transparent}
        div#document h1,div#document h2,div#document h3,div#document h4,div#document h5,div#document h6,div#document p,div#document img{margin:0;padding:0;border:0;outline:0;font-size:100%;vertical-align:baseline;}
        div#document{word-break: break-word; }
        div#document ul{list-style:none}
        blockquote,q{quotes:none;}
        blockquote:before,blockquote:after,q:before,q:after{content:'';content:none;}
        /*remember to define focus styles!*/:focus{outline:0;}
        /*remember to highlight inserts somehow! ins{text-decoration:none;}*/
        div#document del{text-decoration:line-through;}
        /*tables still need 'cellspacing="0"' in the markup*/table{border-collapse:collapse;border-spacing:0;}
        div#document a img{border:none;}
        /*Typography*/

        div#document ul,div#document ol,div#document li{padding:0;}
        div#document ul li, div#document ol li{margin:0 0 2pt 7pt;padding:0 0 0 13pt;vertical-align:baseline;line-height:16pt;clear:both;position:relative;}
        div#document li:before {content: "\2022";font-size: 12pt;position:absolute;left:0;top:1pt;}
        div#document ol{margin:0 0 0 11pt;}
        div#document ol li{list-style-type:decimal}
        /*END Image treatment for LI*/
        div#document .clear {clear: both;height: 0;}
        div#document br.clear{line-height: 0}
        div#document div.name{font-size: 31pt; line-height:31pt;font-weight:700; text-align: center;padding: 0}
        div#document div.name span.lName{color: #4d6e92;}
        div#document div.logo{display: none;}
        div#document div.paragraph{position: relative;;color: #333}
        div#document div.heading {clear: both;font-weight: bold;}
        div#document div.address {
        line-height:16pt;
        color:#767673;
        font-weight:300;
        position: relative;
        text-align: center;
        padding: 0 5pt 10pt;
        word-wrap: break-word;
        }

        div#document  .datesWrapper{ font-weight:400;}
        div#document span.paddedline{ display: block; font-weight:300;}
        div#document span.jobtitle,
        div#document span.degree{font-weight:700;line-height:12pt}
        div#document span.companyname,
        div#document span.programline,
        div#document span.joblocation{font-weight:500}
        div#document .nodisplay{display: none;}
        div#document .adnlLnks li:before{ vertical-align: bottom;}
        div#document .adnlLnks li.first:before {content: "";}
        div#document div.adnlLnks{text-align: center}
        div#document .adnlLnks li {display:inline!important;}
        div#document .bottomborder {border-bottom: 1pt solid #4d6e92;}
        div#document {-webkit-print-color-adjust: exact;line-height:12pt;color:#333}
        div#document .skillSection:after{content:'';clear:both;display:table}
        div#document div.skillSection .paragraph{width:33.333%; float:left}
        div#document div.skillSection .paragraph.firstparagraph{margin-top:1pt;}
        div#document div.skillSection .paragraph:nth-child(3n+5){clear:both}
        div#document div.skillSection .field{margin-left: 22pt;margin-bottom: 7pt;padding-right:4pt}
        div#document div.skillSection .field:before{content: "\2022";font-size: 12pt;position:absolute;left:10pt;top:1pt;}
        div#document div.skillSection .field:empty{display: inline;}
        div#document div.skillSection .field:empty:before{content:"";position:static;}
        div#document em {font-style: italic;}
        div#document strong, div#document b{font-weight:700;}
        div#document.pagesize {width:536pt;box-sizing:border-box}
        div#document .section {padding-top: 10pt;padding-bottom: 10pt;}
        div#document .SECTION_NAME.section {padding-bottom: 0;}
        div#document div.firstsection,div#document div.SECTION_CNTC  {padding-top: 0;}
        div#document div.heading{margin-bottom:1pt;border-bottom: 1pt solid #333333;font-weight:700;width:100%; text-align: center;text-transform:uppercase;margin-bottom:8pt;line-height:11px}
        div#document div.paragraph {margin-top: 1pt;font-size:inherit}
        div#document div.firstparagraph {margin-top: 0;}
        div#document .singlecolumn,div#document .maincolumn{margin-left:0;width:100% !important ; font-weight:300;line-height:14pt}
        div#document .bottomborder {border-bottom: 5pt solid;}

        div#document .section .paragraph .address2{line-height:16pt;}
        /*FIX for Re-calculating width of singlecolumn for CL*/
        div#document .sectionCL .singlecolumn {margin-left: 0!important;line-height:17pt;}
        div#document span.jobcity,span.jobstate,span.jobcountry{font-weight:500;}
        div#document span.text-break{display:block;margin-bottom:10pt}
        
		div#document .section.photo-cv{width:67pt; height:67pt;margin:0 auto 10pt;padding:0;}
		div#document .section.photo-cv img{max-width:100%;height: 67pt;width:67pt;border-radius: 50%;}
		
		
		@media print {
        div#document.pagesize{width:100%}
        }
        body{font-feature-settings: "liga" 0; -moz-font-feature-settings: "liga" off;}
    </style>
    <style type="text/css" id="unparsed">
        div#document.vmargins {padding-top: {$TBMR}pt; padding-bottom: {$TBMR}pt;}
        div#document.hmargins {padding-left: {$LRMR}in; padding-right: {$LRMR}in;}
        div#document.fontsize {font-size: {$FTSZ}pt; font-weight:300}
        div#document.fontface{font-family:{$FTFC};}
        div#document div.sectiontitle {font-size:{$HDSZ}pt; line-height: 19pt;}

        /* Color ribbon styles */

        div#document div.name {color: {$HDCL}}

        /* Color ribbon Styles ENDS HERE */
		
		@media only screen and (min-width: 768px) and (max-width: 991px){
			div#document.hmargins{padding-left:{$LRMRT}in;padding-right:{$LRMRT}in;}
		}
		
        /*  used LRMRM for mobile  */
        @media only screen and (max-width: 767px){
        div#document.hmargins{padding-left:{$LRMRM}in;padding-right:{$LRMRM}in;}
        }
    </style>
    <style type="text/css" id="dynamic">
        div#document.vmargins {padding-top: 28pt; padding-bottom: 28pt;}
        div#document.hmargins {padding-left: 1in; padding-right: 1in;}
        div#document.fontsize {font-size: 9pt; font-weight:300}
        div#document.fontface{font-family:Hind;}
        div#document div.sectiontitle {font-size:11pt; line-height: 19pt;}

        /* Color ribbon styles */

        div#document div.name {color: #6da8ba}

        /* Color ribbon Styles ENDS HERE */
		
		@media only screen and (min-width: 768px) and (max-width: 991px){
			div#document.hmargins{padding-left:0.4in;padding-right:0.4in;}
		}
		
        /*  used LRMRM for mobile  */
        @media only screen and (max-width: 767px){
        div#document.hmargins{padding-left:0.2in;padding-right:0.2in;}
        }
    </style>
  </head>
  <body>
    <div id="document" class="RND fontsize fontface vmargins hmargins linespacing pagesize">
      <div id="SECTION_NAMEb66f5e17-e718-460c-912e-e9bb9e8af038" class="section SECTION_NAME firstsection" style="
      padding-top:NaNpx;
    ">
        <div id="PARAGRAPH_b66f5e17-e718-460c-912e-e9bb9e8af038_1" class="paragraph PARAGRAPH_NAME firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="name">
                    <span class="field" id="b66f5e17-e718-460c-912e-e9bb9e8af038FNAM1">Brendan</span> <span>
                    </span><span class="field" id="b66f5e17-e718-460c-912e-e9bb9e8af038LNAM1">Glancy</span>
                </div>
            </div>
      </div>
      <div id="SECTION_CNTC4cc6c974-77f2-4c49-ba38-62b86311ab81" class="section SECTION_CNTC" style="
      padding-top:NaNpx;
    ">
        <div id="PARAGRAPH_4cc6c974-77f2-4c49-ba38-62b86311ab81_1" class="paragraph PARAGRAPH_CNTC firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="address">
                    <span class="field" dependency="EMAI" id="4cc6c974-77f2-4c49-ba38-62b86311ab81EMAI1">bglance68@gmail.com</span><span> | </span>
                    <span class="field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81HPHN1"></span>
                    
                    <span class="field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81CPHN1">3303125293</span>
                    <br />
                    <span class="field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81STRT1">1385 Circle Hill Rd</span><span><span>, </span></span>
                    <span class="spaced field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81CITY1">North Canton</span><span><span>, </span></span>
                    <span class="spaced field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81STAT1">OHIO</span><span>  </span>
                    <span class="spaced field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81ZIPC1">44720</span>
					<span class="spaced field" id="4cc6c974-77f2-4c49-ba38-62b86311ab81CNTY1"></span>
                </div>
            </div>
      </div>
      <div id="SECTION_SUMM2dd1707c-9312-48f1-a8ba-4430ad5eaa53" class="section" style="
      padding-top:NaNpx;
    ">
        <div class="heading bottomborder">
                <div id="SECTNAME_SUMM2dd1707c-9312-48f1-a8ba-4430ad5eaa53" class="sectiontitle">Professional Summary</div>
            </div>
        <div id="PARAGRAPH_2dd1707c-9312-48f1-a8ba-4430ad5eaa53_1" class="paragraph firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="field singlecolumn" id="2dd1707c-9312-48f1-a8ba-4430ad5eaa53FRFM1"><p>Knowledgeable Web Developer with advanced coding abilities and enthusiasm for new enhancements. Expert in building high-performing, scalable well structures for today and future client needs. Advanced in Java and Python programming languages.</p></div>
            </div>
      </div>
      <div id="SECTION_HILTa5abb724-8ccd-47fb-a58f-414010c79135" class="section skillSection" style="
      padding-top:NaNpx;
    ">
        <div class="heading bottomborder">
                <div id="SECTNAME_HILTa5abb724-8ccd-47fb-a58f-414010c79135" class="sectiontitle">Skills</div>
            </div>
        <div id="PARAGRAPH_a5abb724-8ccd-47fb-a58f-414010c79135_1" class="paragraph firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn maincolumn">
                    <div class="field" id="a5abb724-8ccd-47fb-a58f-414010c79135FRFM1">Python</div>
                </div>
            </div>
        <div id="PARAGRAPH_a5abb724-8ccd-47fb-a58f-414010c79135_2" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn maincolumn">
                    <div class="field" id="a5abb724-8ccd-47fb-a58f-414010c79135FRFM2">JavaScript</div>
                </div>
            </div>
        <div id="PARAGRAPH_a5abb724-8ccd-47fb-a58f-414010c79135_3" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn maincolumn">
                    <div class="field" id="a5abb724-8ccd-47fb-a58f-414010c79135FRFM3">C#</div>
                </div>
            </div>
        <div id="PARAGRAPH_a5abb724-8ccd-47fb-a58f-414010c79135_4" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn maincolumn">
                    <div class="field" id="a5abb724-8ccd-47fb-a58f-414010c79135FRFM4">React</div>
                </div>
            </div>
        <div id="PARAGRAPH_a5abb724-8ccd-47fb-a58f-414010c79135_5" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn maincolumn">
                    <div class="field" id="a5abb724-8ccd-47fb-a58f-414010c79135FRFM5">Vue</div>
                </div>
            </div>
        <div id="PARAGRAPH_a5abb724-8ccd-47fb-a58f-414010c79135_6" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn maincolumn">
                    <div class="field" id="a5abb724-8ccd-47fb-a58f-414010c79135FRFM6">JQuery</div>
                </div>
            </div>
      </div>
      <div id="SECTION_EXPR3a868e59-ed09-4cea-ade5-8067a1ea1e72" class="section" style="
      padding-top:NaNpx;
    ">
        <div class="heading bottomborder">
                <div id="SECTNAME_EXPR3a868e59-ed09-4cea-ade5-8067a1ea1e72" class="sectiontitle">Experience</div>
            </div>
        <div id="PARAGRAPH_3a868e59-ed09-4cea-ade5-8067a1ea1e72_1" class="paragraph firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn">
                    <span class="paddedline">
                        <span class="jobtitle" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JTIT1">Information Technology / Web Developer</span><span></span>
                    </span>
                    <span class="paddedline">
                        <span class="companyname" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72COMP1">Canton Chamber of Commerce</span><span><span> – </span></span>
                        <span class="joblocation jobcity" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JCIT1">North Canton</span><span>, </span>
                        <span class="joblocation jobstate" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JSTA1">OHIO</span>
						<span class="joblocation jobcountry" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JCNT1"></span>
						<span>
							<span> | </span>
						</span>
                        <span class="datesWrapper">
                            <span class="jobdates" format="%B %Y" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JSTD1">August 2019</span><span> - </span>
                            <span class="jobdates" format="%B %Y" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72EDDT1">Current</span><br />
                        </span>
                    </span>
                    <span class="jobline text-break" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JDES1"><ul>
  <li>Attracted users to websites with attractive, user-friendly designs and clean code for high-performance operation.</li>
  <li>Developed and deployed successful e-commerce strategies into clients' websites.</li>
  <li>Produce high-quality, clean code for client projects, including sites such as &nbsp;dwntwncanton.com and starksafetycouncil.org.</li>
  <li>Protected company information with the creation of robust information security systems and effective disaster recovery plans.</li>
</ul></span>
                </div>
            </div>
        <div id="PARAGRAPH_3a868e59-ed09-4cea-ade5-8067a1ea1e72_2" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn">
                    <span class="paddedline">
                        <span class="jobtitle" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JTIT2">Crew Member</span><span></span>
                    </span>
                    <span class="paddedline">
                        <span class="companyname" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72COMP2">Wendys</span><span><span> – </span></span>
                        <span class="joblocation jobcity" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JCIT2">North Canton</span><span>, </span>
                        <span class="joblocation jobstate" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JSTA2">OHIO</span>
						<span class="joblocation jobcountry" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JCNT2"></span>
						<span>
							<span> | </span>
						</span>
                        <span class="datesWrapper">
                            <span class="jobdates" format="%B %Y" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JSTD2">April 2019</span><span> - </span>
                            <span class="jobdates" format="%B %Y" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72EDDT2">August 2019</span><br />
                        </span>
                    </span>
                    <span class="jobline text-break" id="3a868e59-ed09-4cea-ade5-8067a1ea1e72JDES2"><ul>
  <li>Maintained high cleanliness and health code standards.</li>
  <li>Delivered great service to every guest.</li>
  <li>Prepared foods according to menu standards, safety policies, and company policies</li>
  <li>Cross-trained in multiple positions to easily step in and fill needs during busy periods.</li>
</ul></span>
                </div>
            </div>
      </div>
      <div id="SECTION_EDUC9bebcc38-ac2d-4952-8965-1b2bc64cae29" class="section" style="
      padding-top:NaNpx;
    ">
        <div class="heading bottomborder">
                <div id="SECTNAME_EDUC9bebcc38-ac2d-4952-8965-1b2bc64cae29" class="sectiontitle">Education</div>
            </div>
        <div id="PARAGRAPH_9bebcc38-ac2d-4952-8965-1b2bc64cae29_1" class="paragraph firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn">
                    
                    <span class="paddedline">
                        <span class="companyname companyname_educ" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SCHO1">Tech Elevator</span><span><span> | </span></span>
                        <span class="joblocation jobcity" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SCIT1">Cleveland</span><span>, </span>
                        <span class="joblocation jobstate" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SSTA1">OH</span>
                        <span class="joblocation jobcountry" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SCNT1"></span>
                        <span><span> | </span></span>
                        <span class="datesWrapper">
                            <span class="jobdates" format="%B %Y" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29GRDT1">December 2020</span>
                        </span>
						
						 
                    </span>

                    <span class="field text-break" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29FRFM1">14 week Java coding Bootcamp focused on developing dynamic web-based software systems using the Java 
programming language and platform.</span>
                </div>
            </div>
        <div id="PARAGRAPH_9bebcc38-ac2d-4952-8965-1b2bc64cae29_2" class="paragraph" style="
      padding-top:NaNpx;
    ">
                <div class="singlecolumn">
                    
                    <span class="paddedline">
                        <span class="companyname companyname_educ" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SCHO2">Hoover High School</span><span><span> | </span></span>
                        <span class="joblocation jobcity" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SCIT2">North Canton</span><span>, </span>
                        <span class="joblocation jobstate" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SSTA2">OH</span>
                        <span class="joblocation jobcountry" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29SCNT2">Test</span>
                        <span><span> | </span></span>
                        <span class="datesWrapper">
                            <span class="jobdates" format="%B %Y" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29GRDT2">May 2020</span>
                        </span>
						
						 
                    </span>

                    <span class="field text-break" id="9bebcc38-ac2d-4952-8965-1b2bc64cae29FRFM2"></span>
                </div>
            </div>
      </div>
      <div id="SECTION_OTHR5951a33d-0401-406f-8ee7-0910f06bad98" class="section" style="
      padding-top:NaNpx;
    ">
        <div class="heading bottomborder">
                <div id="SECTNAME_OTHR5951a33d-0401-406f-8ee7-0910f06bad98" class="sectiontitle">Projects</div>
            </div>
        <div id="PARAGRAPH_5951a33d-0401-406f-8ee7-0910f06bad98_1" class="paragraph firstparagraph" style="
      padding-top:NaNpx;
    ">
                <div class="field singlecolumn" id="5951a33d-0401-406f-8ee7-0910f06bad98FRFM1"><ul>
  <li><strong>Kiss Landscaping</strong> - React app using styled components and react scroll. Deployed to a custom domain with FTP and SSL certificate. Mobile and desktop styling</li>
  <li><strong>Banking Software</strong> - Developed a Venmo-like application in Java that inputs to and from Postgres database, tracks account balances, records transfers, demonstrates knowledge of concepts such as Spring Web MVC, JDBC, DAO, REST APIs &nbsp;</li>
  <li><strong>Personal Portfolio -</strong> website built with react, styled beautifully for mobile and desktop&nbsp;</li>
  <li><strong>Beverage Rating Platform</strong> - Vue app with a Postgres backend, large database with information relevant to Cleveland area, built in admin functions and client functions<br>
</li>
</ul></div>
            </div>
      </div>
    </div>
  </body>
</html>
