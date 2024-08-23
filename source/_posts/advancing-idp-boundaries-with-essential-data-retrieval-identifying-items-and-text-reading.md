---
title: Advancing IDP Boundaries with Essential Data Retrieval, Identifying Items and Text Reading
date: 2024-08-22T00:01:45.887Z
updated: 2024-08-23T00:01:45.887Z
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/1477ca2012895e861bfdb26b444c7a0eb6d638cc1df6527be4105c5f43b0af39.jpg
---

## Advancing IDP Boundaries with Essential Data Retrieval, Identifying Items and Text Reading

[Back to The Intelligent Enterprise](https://tools.techidaily.com/abbyy/products/)

## Pushing the Boundaries of IDP: Object Detection, Word Recognition, and Key-Value Extraction

###### by Max Vermeir, Senior Director of AI Strategy

One of the most defining characteristics of IDP is the strategic use of AI as the core foundation for automating document-centric tasks. ABBYY developers explain three exciting new AI models that are pushing the boundaries of IDP in key-value extraction, object detection, and word recognition.

One of the most defining characteristics of intelligent document processing (IDP) is the strategic use of artificial intelligence (AI) as the core foundation for automating document-centric tasks. AI models and algorithms enable contextual understanding to improve speed and accuracy, driving business value for customers with document-heavy workflows. 

[ABBYY Vantage](https://tools.techidaily.com/abbyy/products/) exemplifies this concept with its library of pre-trained “skills,” also known as pre-trained AI document processing models. By narrowing the scope of an AI solution to excel at a specific task, these purpose-built AI skills work efficiently to accelerate outcomes in specialized contexts. 

In a recent showcase session presented by the ABBYY research and development team, our developers Konstantin Anisimovich, Evgenii Orlov, Ivan Zagaynov, and Andrew Upshinskiy explained three exciting new AI models that are pushing the boundaries of IDP in key-value extraction, object detection, and word recognition.

#### 1\. Key-value extraction 

Identifying key information is an essential Vantage skill that allows for actionable data to be extracted from a document type. Document-specific models at the core of the skill are trained to identify fields such as “company name,” “address,” or “zip code,” enabling the corresponding values to be extracted. Separate models are made for different document types, determining the fields that the model will look for.

This process is known as **key-value pairs extraction**. This entails finding all possible “keys,” or field names; all possible “values,” which are the contents of those fields; as well as the associations between keys and corresponding values. But how is the model trained to make these associations?

Taking a large, general key-value extraction model and training it on a set of documents allows the model to build proficiency in automatic markup. Through a process called **knowledge distillation**, or the transferring of knowledge from a large AI model to a smaller one, more specialized AI models can be built that operate at a lower computational cost and greater inference speeds, than their larger counterparts.

ABBYY’s current path towards this solution consists of two independent workflows: entity extraction and linking models for general documents, and key summarization and QA models for text-heavy documents such as contracts. Both models are based on the transformer architecture that is ubiquitous in modern neural networks, e.g., the GPT-family and other LLMs.

![pushing-the-boundaries-of-idp-2](https://content.abbyy.com/-/media/project/abbyy/abbyy/insights/intelligent-enterprise/content-media/pushing-the-boundaries-of-idp-2.png)

The image above portrays a form-like document where green highlights indicate keys, and yellow highlights indicate values that must be extracted from their respective keys. In a form, there are visual indicators such as layouts and blank cells that suggest where key-values lie. The world classification model tags each word as either a background or a part of a key or value, while the entity linking model combines the tagged words into key/value sequences and matches them together. Within this workflow, text is processed by a RoBERTa transformer, while visual data (images) are processed by a compact YOLOv8 model.

For text-heavy documents, a text summarization model extracts a list of all keys from the document, and a question-answering model finds corresponding value excerpts using information about the key. Once again, two separate models are used in this workflow: for key extraction, an encoder-decoder architecture uses a multimodal LayoutLM-like transformer encoder to extract rich features from the data, and a BART transformer decoder extracts relevant key word sequences using the encoded data. The value extraction model is based on a RoBERTa transformer and employs query paraphrasing and adversarial data to enhance performance.

Webinar

#### The AI within Your IDP Platform

[Learn more](https://tools.techidaily.com/abbyy/products/)

#### 2\. Detecting objects in a document image

Object detection is a crucial stage of document processing, as elementary objects must eventually be extracted from the document. This entails estimating the size of the text, correcting the skew of a page, adjusting images to a normalized state, and other variables before objects can be extracted.

A document can be thought of as a “bag of objects,” with such objects including signatures, stamps, checkmarks, separators, barcodes, printed and handwritten text, and other possible entities.

Historically, there have been two approaches to this detection: classic methods and neural networks.

Classic methods are based on well-known and trusted algorithms but tend to be limited in their ability to handle photos and corrupted documents. This can introduce complications when dealing with shadows, distortion, and other forms of visual noise, impacting results in the object detection stage. Neural networks, by contrast, are a state-of-the-art solution that ABBYY has already used for over five years, yielding optimal results in detecting various kinds of objects. However, this requires a neural network for each object type, making this approach unfeasible when detecting multiple object varieties.

As such, ABBYY came to a solution involving a universal feature extractor common to several object detection nets within a neural network. This “backbone net” delegates feature extraction to several detection heads, each with a unique architecture allowing them to detect a specific object.

To consume less processing power in contexts requiring simultaneous data processing, this solution breaks document pages into several overlapping stripes, preserving objects that may occur at the boundary of each section. After processing each stripe, the contained objects are fed to detection heads and used for future tasks such as maintaining document structure or reconstructing paragraphs and tables. This process is called single-page parallel processing, as each striped section of a document can be processed by their respective detection heads in parallel.

#### 3\. Advanced word recognition

Traditional OCR involves an input of a line image containing text that then yields an output of a Unicode text sequence. The classic approach segments to approximate one-word fragments, finds the hypothesis for character segmentation points using a linear division graph, and finally constructs words from these hypotheses.

This approach can have complications. Segmentation points are often found heuristically; when the heuristic assumption is inadequate, the process will not work. In some languages, like Arabic and Bengali, there isn’t an easy heuristic case. This is also the case for handwritten text, which would require a level of script accuracy that is rare in handwriting.

As such, ABBYY developed an end-to-end approach for both handwritten and printed text recognition. An entire text sequence is extracted at once, removing the need for establishing boundaries within the document.

In printed cases, these documents are easy to identify elements and markup accordingly. This is an easier task for a neural network—the scan quality rate of the Latin model is 99.8 percent. The only flaw is inherent to the speed/quality balance. 

The architecture for end-to-end OCR generally consists of three parts: the backbone (visual transformer), which is responsible for image extraction; sequential modeling (transformer encoder), which is needed for some contextual features in an overall sequence; and the decoder, which is the algorithm determining how the text is ultimately written considering the feature set and previous steps in the process. This pipeline is then supplemented with ABBYY’s LLM that takes into account all the context of the recognition process and provides enhanced output of the recognized text, leading to incredible accuracy rates, especially in low-quality documents.

#### Evolving IDP: driving efficiency and versatility

The advances to ABBYY’s AI models reflect enterprises’ increasing need for agility and efficiency in document processing, not only in processing time, but also in energy consumption and general versatility. 

By broadening the capabilities of modern OCR with improved object detection, more inclusive word recognition, and the reliable extraction of actionable key values, ABBYY is expanding the scope of how intelligent document processing can transform business-critical processes.

Visit [abbyy.com/vantage](https://tools.techidaily.com/abbyy/products/) to learn more about purpose-built AI in IDP.

#### Subscribe for updates

Get updated on the latest insights and perspectives for business & technology leaders

First name\*

Last name

E-mail\*

Сountry\*

СountryAfghanistanAland IslandsAlbaniaAlgeriaAmerican SamoaAndorraAngolaAnguillaAntarcticaAntigua and BarbudaArgentinaArmeniaArubaAustraliaAustriaAzerbaijanBahamasBahrainBangladeshBarbadosBelgiumBelizeBeninBermudaBhutanBoliviaBonaire, Sint Eustatius and SabaBosnia and HerzegovinaBotswanaBouvet IslandBrazilBritish Indian Ocean TerritoryBritish Virgin IslandsBrunei DarussalamBulgariaBurkina FasoBurundiCambodiaCameroonCanadaCape VerdeCayman IslandsCentral African RepublicChadChileChinaChristmas IslandCocos (Keeling) IslandsColombiaComorosCongo (Brazzaville)Congo, (Kinshasa)Cook IslandsCosta RicaCroatiaCuraçaoCyprusCzech RepublicCôte d'IvoireDenmarkDjiboutiDominicaDominican RepublicEcuadorEgyptEl SalvadorEquatorial GuineaEritreaEstoniaEthiopiaFalkland Islands (Malvinas)Faroe IslandsFijiFinlandFranceFrench GuianaFrench PolynesiaFrench Southern TerritoriesGabonGambiaGeorgiaGermanyGhanaGibraltarGreeceGreenlandGrenadaGuadeloupeGuamGuatemalaGuernseyGuineaGuinea-BissauGuyanaHaitiHeard and Mcdonald IslandsHoly See (Vatican City State)HondurasHong Kong, SAR ChinaHungaryIcelandIndiaIndonesiaIraqIrelandIsle of ManIsraelITJamaicaJapanJerseyJordanKazakhstanKenyaKiribatiKorea (South)KuwaitKyrgyzstanLao PDRLatviaLebanonLesothoLiberiaLibyaLiechtensteinLithuaniaLuxembourgMacao, SAR ChinaMacedonia, Republic ofMadagascarMalawiMalaysiaMaldivesMaliMaltaMarshall IslandsMartiniqueMauritaniaMauritiusMayotteMexicoMicronesia, Federated States ofMoldovaMonacoMongoliaMontenegroMontserratMoroccoMozambiqueMyanmarNamibiaNauruNepalNetherlandsNetherlands AntillesNew CaledoniaNew ZealandNicaraguaNigerNigeriaNiueNorfolk IslandNorthern Mariana IslandsNorwayOmanPakistanPalauPalestinian TerritoryPanamaPapua New GuineaParaguayPeruPhilippinesPitcairnPolandPortugalPuerto RicoQatarRomaniaRwandaRéunionSaint HelenaSaint Kitts and NevisSaint LuciaSaint Pierre and MiquelonSaint Vincent and GrenadinesSaint-BarthélemySaint-Martin (French part)SamoaSan MarinoSao Tome and PrincipeSaudi ArabiaSenegalSerbiaSeychellesSierra LeoneSingaporeSint Maarten (Dutch part)SlovakiaSloveniaSolomon IslandsSouth AfricaSouth Georgia and the South Sandwich IslandsSouth SudanSpainSri LankaSurinameSvalbard and Jan Mayen IslandsSwazilandSwedenSwitzerlandTaiwan, Republic of ChinaTajikistanTanzania, United Republic ofThailandTimor-LesteTogoTokelauTongaTrinidad and TobagoTunisiaTurkeyTurks and Caicos IslandsTuvaluUgandaUkraineUnited Arab EmiratesUnited KingdomUnited States of AmericaUruguayUS Minor Outlying IslandsUzbekistanVanuatuVenezuela (Bolivarian Republic)Viet NamVirgin Islands, USWallis and Futuna IslandsWestern SaharaZambiaZimbabwe

* I have read and agree with the [Privacy policy](https://tools.techidaily.com/abbyy/products/) and the [Cookie policy](https://tools.techidaily.com/abbyy/products/).\*

* I agree to receive email updates from ABBYY Solutions Ltd. such as news related to ABBYY Solutions Ltd. products and technologies, invitations to events and webinars, and information about whitepapers and content related to ABBYY Solutions Ltd. products and services.  
    
I am aware that my consent could be revoked at any time by clicking the unsubscribe link inside any email received from ABBYY Solutions Ltd. or via [ABBYY Data Subject Access Rights Form](https://tools.techidaily.com/abbyy/products/).

Referrer

Query string

GA Client ID

UTM Campaign Name

UTM Source

UTM Medium

UTM Content

ITM Source

Page URL

Captcha Score

Connect with us

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-streamlining-your-social-video-logs-on-facebook/"><u>[New] 2024 Approved  Streamlining Your Social Video Logs on Facebook</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-facebook-launching-your-first-phenomenal-giving-post/"><u>[New] Facebook  Launching Your First Phenomenal Giving Post</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-iphones-visual-upgrades-in-ios-11-explored/"><u>[New] IPhone's Visual Upgrades in iOS 11 Explored</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-perfectly-suited-8-recommended-tools-for-subtitles-and-srts/"><u>[New] Perfectly Suited  8 Recommended Tools for Subtitles & SRTs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-pioneering-visual-stunts-from-the-ground-up/"><u>[New] Pioneering Visual Stunts From the Ground Up</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-sunny-side-up-videography-for-android/"><u>[New] Sunny Side-Up Videography for Android</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-syma-x5c-exposed-perfect-pick-for-novice-aerial-enthusiasts/"><u>[New] Syma X5C Exposed  Perfect Pick for Novice Aerial Enthusiasts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-thorough-review-of-videoshow-24-features-and-updates/"><u>[New] Thorough Review of VideoShow '24 Features & Updates</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-4k-camera-guide-top-6-dslrs-reviewed/"><u>[New] Ultimate 4K Camera Guide  Top 6 DSLRs Reviewed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-understanding-and-leveraging-telegram-browser-features/"><u>[New] Understanding and Leveraging Telegram Browser Features</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/outubes-trophy-chain-for-engaged-audiences-for-2024/"><u>[New] YouTube's Trophy Chain for Engaged Audiences for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-how-to-use-zoom-on-xbox-one/"><u>[Updated] How to Use Zoom on Xbox One</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-strategies-to-extend-gopro-battery-hours/"><u>[Updated] Strategies to Extend GoPro Battery Hours</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-art-of-crafting-gopro-time-lapses/"><u>[Updated] The Art of Crafting GoPro Time-Lapses</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ethical-path-to-engaging-interviews/"><u>[Updated] The Ethical Path to Engaging Interviews</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-ultimate-guide-to-scheduling-zoom-events-for-2024/"><u>[Updated] The Ultimate Guide to Scheduling Zoom Events for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-vr-bikes-to-check-out/"><u>[Updated] Top VR Bikes to Check Out</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-typhoon-h-unveiled-yuneecs-aerial-marvel/"><u>[Updated] Typhoon H Unveiled  Yuneec's Aerial Marvel</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-stop-automatically-added-podcast-episodes-via-spotifys-suggestions/"><u>2024 Approved  Stop Automatically Added Podcast Episodes via Spotify's Suggestions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-superior-plot-strategies-across-diverse-cinematic-fields/"><u>2024 Approved  Superior Plot Strategies Across Diverse Cinematic Fields</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-art-of-photo-to-video-with-accompaniment-sounds/"><u>2024 Approved  The Art of Photo-to-Video with Accompaniment Sounds</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-samsung-revolution-diving-deep-into-the-ue590-monitor-review/"><u>2024 Approved  The Samsung Revolution - Diving Deep Into the UE590 Monitor Review</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-meta-and-omni-versions/"><u>2024 Approved  The Ultimate Guide to Meta & Omni Versions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-premier-sound-storylines/"><u>2024 Approved  Top Premier Sound Storylines</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transform-voice-with-cloud-services-top-5-online-chromebook-audio-editors/"><u>2024 Approved  Transform Voice with Cloud Services  Top 5 Online Chromebook Audio Editors</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleash-creativity-complimentary-premiere-pro-toolset/"><u>2024 Approved  Unleash Creativity - Complimentary Premiere Pro Toolset</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-the-full-capabilities-of-zoom-on-windows-10-pcs/"><u>2024 Approved  Unlocking The Full Capabilities of Zoom on Windows 10 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209058550-aoc-monitors-not-showing-up-get-them-working-on-windows-11-with-these-fixes/"><u>AOC Monitors Not Showing Up? Get Them Working on Windows 11 with These Fixes!</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-ps5-mistake-4-warning-signs/"><u>Avoid PS5 Mistake: 4 Warning Signs</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-to-setting-up-amd-miners-on-a-windows-pc-downloads-included/"><u>Guide to Setting Up AMD Miners on a Windows PC: Downloads Included</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-nubia-z50-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-factory-unlock-your-telstra-apple-iphone-15-by-drfone-ios/"><u>In 2024, How To Factory Unlock Your Telstra Apple iPhone 15</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-previewed-activities-on-facebook-are-you-exposed/"><u>In 2024, Previewed Activities on Facebook  Are You Exposed?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-essential-handbook-for-periscope-video-logging/"><u>In 2024, The Essential Handbook for Periscope Video Logging</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-clearer-eliminate-backgrounds-effectively/"><u>In 2024, Ultimate Clearer  Eliminate Backgrounds Effectively</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-iphone-strategies-for-flawless-audio-downloads/"><u>In 2024, Ultimate iPhone Strategies for Flawless Audio Downloads</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlock-the-best-places-to-explore-vector-artwork-at-no-cost/"><u>In 2024, Unlock the Best Places to Explore Vector Artwork at No Cost</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/leading-8-open-source-video-chat-solutions-for-businesses/"><u>Leading 8 Open Source Video Chat Solutions for Businesses</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-essential-guide-to-metaverse-brand-strategies-for-2024/"><u>The Essential Guide to Metaverse Brand Strategies for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-s17e-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo S17e Phone Pattern Lock</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-your-images-with-text-a-windowsmacos-expertise-guide-for-2024/"><u>Transform Your Images with Text  A Windows/MacOS Expertise Guide for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-choice-for-gif-to-video-online-tools-best-5-for-2024/"><u>Ultimate Choice for GIF-to-Video Online Tools (Best 5) for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-the-full-potential-of-iphones-hdr-capabilities-for-2024/"><u>Unlocking the Full Potential of iPhone's HDR Capabilities for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/urgent-top-10-lost-iphone-x-solutions-revealed-for-2024/"><u>Urgent  Top 10 Lost iPhone X Solutions Revealed for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->

<!-- affiliate ads end -->