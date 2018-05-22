# hydro-auth

 <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-java-library-for-hydro-raindrop-api" class="anchor" aria-hidden="true" href="#java-library-for-hydro-raindrop-api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Java library for Hydro Raindrop Api</h1>
<p><a target="_blank" href="https://camo.githubusercontent.com/af50fae560ac958908dee6d97f74531be509d599/68747470733a2f2f7777772e687964726f67656e706c6174666f726d2e636f6d2f696d616765732f6c6f676f5f687964726f2e706e67"><img src="https://camo.githubusercontent.com/af50fae560ac958908dee6d97f74531be509d599/68747470733a2f2f7777772e687964726f67656e706c6174666f726d2e636f6d2f696d616765732f6c6f676f5f687964726f2e706e67" data-canonical-src="https://www.hydrogenplatform.com/images/logo_hydro.png" style="max-width:100%;"></a></p>
<h2><a id="user-content-introduction" class="anchor" aria-hidden="true" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Introduction</h2>
<p>The Hydro Smart Contract is open source blockchain software developed by <a href="https://www.hydrogenplatform.com/" rel="nofollow">Hydrogen Platform</a>.</p>
<p>This java library provides simple usage for raindrop api which is developed by hydrogenplatform.</p>
<p>For more details, please check <a href="https://www.hydrogenplatform.com/docs/hydro/v1/" rel="nofollow">Hydrogen Raindrop Api Docs</a>
</p><h2><a id="user-content-development" class="anchor" aria-hidden="true" href="#development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Development</h2>
<ul>
<li>Java 1.8</li>
<li>Maven 3</li>
<li>HttpClient 4.5.5 (dependency)</li>
</ul>
<pre><code>git clone https://github.com/serkanalgl/hydro-auth.git
cd hydro-auth
mvn clean package
</code></pre>
<p>jar file is available <a href="https://github.com/serkanalgl/hydro-auth/releases/download/1.0.0/hydro-auth.jar">here</a></p>
<h6><a id="user-content-ps-ill-upload-the-artifact-to-central-repository-soon" class="anchor" aria-hidden="true" href="#ps-ill-upload-the-artifact-to-central-repository-soon"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>PS: I'll upload the artifact to central repository soon.</h6>
<h2><a id="user-content-getting-started" class="anchor" aria-hidden="true" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting Started</h2>
<pre><code> IHydroAuthenticator hydroAuthenticator = new HydroAuthenticator("API_KEY", "API_USERNAME", "USE_TESTNET true/false");
</code></pre>
<h3><a id="user-content-step-1-add-address-to-whitelist--be-careful-for-security-purposes-this-id-will-only-be-generated-one-time-" class="anchor" aria-hidden="true" href="#step-1-add-address-to-whitelist--be-careful-for-security-purposes-this-id-will-only-be-generated-one-time-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 1: Add address to whitelist ( be careful, for security purposes, this id will only be generated one time. )</h3>
<pre><code>Whitelist whitelist = hydroAuthenticator.whitelist("Hydro/Ethereum ADDRESS 0x12312..."); 

whitelist.isSuccess(); //api call is success (200)
whitelist.getMessage(); //error response content

whitelist.getHydroAddressId(); //get address id
</code></pre>
<h3><a id="user-content-step-2-get-raindrop-details" class="anchor" aria-hidden="true" href="#step-2-get-raindrop-details"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 2: Get Raindrop details</h3>
<pre><code>Challenge challenge = hydroAuthenticator.challenge("HYDRO_ADDRESS_ID");

whitelist.isSuccess(); //api call is success (200)
whitelist.getMessage(); //error response content

// Set quantity of Hydro tokens to send to the blockchain. Since our token has 18 decimal places, the number that you will need to send may seem large, but remember that the 18 rightmost digits are actually decimals. For example, 313823208533000000 is actually .313823208533000000 Hydro.
challenge.getAmount();

// Randomly generated string used to confirm the validity of the transaction. Only the client requesting the challenge will know the value.
challenge.getChallenge(); 

// The ID assigned to your firm which will be the same for all authentication requests.
challenge.getPartnerId();  
</code></pre>
<h3><a id="user-content-step-3-check-on-exist-valid-raindrop-transaction" class="anchor" aria-hidden="true" href="#step-3-check-on-exist-valid-raindrop-transaction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 3: Check on exist valid Raindrop transaction</h3>
<pre><code>Authenticate authenticate = hydroAuthenticator.authenticate("HYDRO_ADDRESS_ID");

// check is authenticated
authenticate.isAuthenticated();
</code></pre>
<h2><a id="user-content-contact" class="anchor" aria-hidden="true" href="#contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Contact</h2>
<p>If you have any further question/suggestion/issue, do not hesitate to contact me.</p>
<p><a href="mailto:5starairdrop@gmail.com">5starairdrop@gmail.com</a></p>
<h2><a id="user-content-donate" class="anchor" aria-hidden="true" href="#donate"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Donate</h2>
<p>Ethereum: 0x0D3295e1eDe774f622c74E5749714Bec6793A73c</p>
<p>PS: I'm not team member of Hydrogen Platform. I just want to help people who wants to use hydro raindrop api.</p>
</article>
  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>
