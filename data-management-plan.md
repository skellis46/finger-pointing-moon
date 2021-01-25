# data management plan

>The Data Management Plan should outline the project’s approach to managing data. It is mandatory to include for all Leadership Fellows, Research, Development and Engagement Fellowship scheme, Research Grants and Follow on Funding applications but is not required for Research Networking. 

>The data management plan can be up to a maximum of two pages long and can include diagrams, but these must be within the 2-page limits.

>Naming Convention: Surname_DMP

## Data types

>1. Briefly introduce the types of data the research will create. Why did you decide to use these data types?

The fieldwork will be comprehensively documented (Output 1), and will produce still images, video images and spherical 360º video. The still images will be captured with a GoPro Hero 9 as RAW files (5000x4000 pixels, 300dpi in .gpr format). The video images will be captured via GoPro Hero 9 using the HEVC codec (H.265) at 4k and 60fps. HEVC is a modern codec that maximises image quality while keeping file sizes relatively small. The Hero 9 will make still and moving image production as seamless as possible while the researchers are moving, and the file formats created will provide the most flexibility for post-production and output. Spherical 360º video (.360 format) will be captured with a GoPro Max at 6K resolution and stitched to 5.6K Equal Area Cubemaps (EAC) split into two separate video tracks (h.264).[^go] We will use GoPro Player for Desktop to decode both streams and re-project into a sphere ready for .mp4 output. The 360º video will enable rich documentation of the movement practices, and in particular the constantly shifting spatial relationships between the two researchers. 

[^go]: <https://gopro.com/en/us/news/max-tech-specs-stitching-resolution>

The images for exhibitions (Outputs 3 and 4) will be collected as print-suitable 300dpi jpgs. This is a common, flexible and future-proof form of image compression. 

Audio data will be created for the podcast (Output 8), and for providing audio materials for visually impaired audiences for the exhibitions (Outputs 3 and 4). Both sets of data will be recorded as high-resolution 16 bit .wav files at 320kbps, 44.1kHz, and then compressed to 64kbps mono .mp3 files. This is the commonly used format and compression for speech-based podcasts, and will ensure maximum flexibility and accessibility for online production and presentation.

The podcast will be produced and post-produced professionally by Maltstore Communications Ltd/Research Podcasts. It will be hosted off-site by the podcast host Libsyn, but all digital materials will also be stored at CovUni.

The Discourse Forum software is open-source and will be hosted and managed by CovUni (Output 9). It will house user-generated text and web-based media (markdown text files, gifs, jpgs), 

The video essay (Output 7) will combine a range of text, audio and video materials recorded as a "desktop documentary" with screen recording software Screenflow. It will produce a high-definition 1080p .mp4 video (H.264 codec). This will ensure the file is easily able to be stored, uploaded and shared. 

The curated "micro-conferences" (Output 10) will be recorded Zoom conversations that produce .mp4, .m4a audio, and .txt chat data streams. These formats are ideal for any post-production required, and small enough to be easily embedded in the project website.

All video data produced for the project will be uploaded to the C-DaRE Vimeo channel as H.264 mp4 files, 25fps, 10,000kbps, 1920x1080 (with audio: AAC-LC, 320 kbps, 48 kHz). Vimeo uses H.264/AVC codec, an international ISO/ITU standard, and the most used codec for distributing HD video. We will use Vimeo to maximise accessibility and cross platform/device use. Video content will also be permanently and securely stored and backed up via the Coventry University institutional repository.

The project website (Output 11) will be securely hosted and served by Coventry University using the WordPress content management system. WordPress enables maximum design flexibility with industry standard responsive designs. The RA and PI will develop and maintain the site for the length of the project. The content will include project details, a project blog, project outputs, and video embeds (from Vimeo) of materials produced during the project. 

All written materials for the project will be created using markdown text files (.md). This format creates small file sizes and ensures complete future proofing. These text/written materials (including the development of this proposal) will be made publicly available through a GitHub repository: https://github.com/skellis46/finger-pointing-moon.

## Methods to create data

>2. Give details on the proposed methodologies that will be used to create the data. Advise how the project team selected will be suitable for the data/digital aspects of the work, including details of how the institution’s data support teams may need to support the project

The practice-research fieldwork will comprise a series of experiments using the dance form known as Authentic Movement. The two researcher (Ellis (PI) and Whalley (expert input)) will work with recording technologies that do not interfere with their movement yet provide high quality moving and still image data. The key will be to generate a range of rich video materials on which to create experimental document strategies. The PI Ellis is a highly experienced video and web artist-researcher used to working with video and still image production, storage and post-production, and internet-based technologies. He will be responsible for planning and executing the data and digital aspects of the work. He will be supported (when necessary) by CovUni's IT services team, particularly with hosting the Wordpress site and Discourse Forum.

## Data storage and backup

>How the data will be stored in the long term
a. What backup will you have in the in-project period to ensure no data is lost?
b. Where have you decided to store it, why is this appropriate?
c. How long will it be stored for and why?
d. Costs of storage – why are these appropriate? Costs related to long term storage will be permitted providing these are fully justified and relate to the project Full justification must be provided in Justification of Resources (JoR)

All video, photographic, audio, and text data will be uploaded and stored in an internal hosted encrypted Microsoft Sharepoint file repository set up specifically for the project by Coventry University. The repository is fully secure and GDPR compliant, and can store data securely and for five years after the end of the project. The storage is mirrored to a secure ISO27001 off-campus site and subject to a Disaster Recovery Plan. Secure nightly backups are taken. This store will be for the live project data and only authorised people will have access to these data. Coventry University Information Technology Service has processes in place to ensure: the completeness and accuracy of the backed-up data; backup copies of data are stored in a secure manner; data can be restored from a required backup within a reasonable time with authorisation from a data custodian; control of media rotation; secure storage; copies of data are taken on schedule; the secure disposal of data and magnetic media when they are no longer required. There is no storage space limitation for the project and the data will be stored until five years after the end of the project. The costs of data storage will be absorbed by CovUni.

## Sharing and value to others

>5. How the data will be shared and the value it will have to others
a. How the data will enhance the area and how it could be used in the future?
b. Releasing the data – advise when you will be releasing and justify if not releasing in line with AHRC guidelines of a minimum of three years. If the data will have value to different audiences, how these groups will be informed?
c. Will the data need to be updated? Include future plans for updating if this is the case.
d. Will the data be open or will you charge for it? Justify if charging to access the data
e. Financial requirements of sharing – include full justification in the JoR

_Finger Pointing Moon_ will produce multiple Open Access digital outputs online, presented on the project website: i) experimental documentation practices; ii) audio versions of exhibition materials (for visually impaired audiences); iii) selected visual materials from exhibitions; iv) epistemic lexicon; v) blog. Video content produced for the project will be stored securely, compressed for high-definition quality online storage, streaming, and download through C-DaRE's Vimeo account, and embedded in the project website: i) Zoom recordings of curated talks (micro-conferences), ii) video and still-images created during practice-research fieldwork; and iii) desktop documentary (video essay). 

These various multi-media data will be released as they are produced in accordance with the project timeline (within 18 months of the project start date). Audiences will be informed through the project website, and by newsletters and social media posts through project partners, C-DaRE and CovUni. It's not possible to predict (or make claims for) how these data will be useful to other researchers, although at the very least it will act as an example of a radically open and freely available data set for other practice-researchers nationally and internationally. In addition, the transparent process -- along with CC-BY data available globally -- will ensure the project's claims are subject to comprehensive scrutiny. 

The data will not need to be updated, and the costs of sharing (e.g. through Vimeo and Sharepoint) have been absorbed by CovUni.


## Ethical and Legal considerations

>a. Any legal and ethical considerations of collecting the data
>b. Legal and ethical considerations around releasing and storing the data – anonymity of any participants, following promises made to participants

The project will ensure that all ethical and legal considerations are clearly established from the start of the project. We will ensure that the professional dance artists understand the full nature of their involvement and will ensure that we conduct ethical research practice from the start. Whilst we have already explained the proposed research clearly to the dance artists and they have agreed to participate on this basis, we will ensure we get consent for all aspects of the research and make clear that they are free to withdraw from any part of the research at any point. In the unlikely event that it becomes impossible for a dancer to continue due to either being uncomfortable about the research direction, or due to other unforeseen circumstances, we will seek to recruit another professional dancer to maintain the group size and diversity that will be preferred for the project. Some of the information will identify the participants (e.g. video recordings of dancers using the system) and we will ensure that we have consent for using it for our research and further consent for dissemination on the project website, for the exhibition, symposium and for project publications. Participants will be informed that they are free to withhold their consent and will be asked to approve any material that we wish to make public prior to publication so as to ensure that it is both personally and professionally appropriate. If audio recordings are shared we will also agree whether individuals wish to be identified by name. The dance artists will have the opportunity to decide whether their motion capture data can be made public, and which data needs to be kept private. No information beyond that which identifies the dancers within their professional role will be documented or shared. An agreement will be drawn up between the collaborating Universities to clarify Intellectual Property that may arise from the project. 


## other notes from AHRC

>By submitting the application, you are confirming your institution has considered and will meet the following points listed below. Unless the proposal is inherently digital in its methodology and naturally requires the information in these points to be specified and detailed in order to furnish the application you do not need to go into any further detail explaining these points.

>By submitting you are confirming that:
• The proposal has been written in line with your institution’s data management policy
• You have consulted with the institution’s data support (e.g. library services, IT department)
• The institution is able to store the data appropriately during the lifecycle of the grant, the relevant people have been consulted and this has been considered and agreed
• The institution has considered all the risks, and storage will be in line with the institution’s data management policy (provide a link to the policy if applicable)
• The institution will ensure the format/quality of the data (how will you make it as easy as possible to access the data?)
• You have consulted the relevant people in your organisation and you are aware of any IP considerations
• You have considered any data protection requirements
• You have considered the legal considerations of collecting and releasing the data
and have consulted with appropriate support
• The data collection, creation, storage and dissemination will conform to the
institution’s ethical policy
• We expect the Data Management Plan will be revisited each year during the award and as long as is required following the award to take into account any potential changes in (for instance) technology/IP/institutional data management policy/copyright to ensure legal compliance
You must confirm these points via a yes/no box on the application form and we do not expect applications to be submitted if they do not comply. If you do not confirm the institution will comply with these points the proposal will be rejected.