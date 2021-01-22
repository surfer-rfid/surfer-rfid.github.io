# About S.U.R.F.E.R.

<b>S.U.R.F.E.R</b> is an acronym for: 
<b>S</b>oftware-Defined <b>U</b>HF <b>R</b>FID 
<b>F</b>lexible <b>E</b>conomical <b>R</b>eader.

Broadly, the goal of the S.U.R.F.E.R. program is to increase the 
proliferation of UHF RFID and other long-range backscatter technologies 
worldwide.

# What is UHF RFID?

<center><img src="https://github.com/surfer-rfid/surfer-rfid.github.io/blob/main/RFIDConcept011921.png" width="50%"></center>

UHF RFID is a technology in which a reader and a tag communicate at a 
distance of up to 2 to 20 meters, depending on the specifics of the setup.
The reader interrogates the tag to obtain information such as a unique ID
or environmental characteristics, such as temperature or air pressure.

UHF RFID tags are either active or passive. Active UHF RFID tags are partially
powered by a battery, while passive tags are not. Passive UHF RFID tags are incredibly 
cheap, ranging down to $0.05 per tag in bulk, and often come with adhesive backing. 
This means that they can be deployed quickly and <i>en masse</i>, with little regard
to long-term maintenance requirements.

# Where is UHF RFID used?

<center><img src="https://github.com/surfer-rfid/surfer-rfid.github.io/blob/main/UHF_RFID_Uses_011921.png" width="50%"></center>

Typically, UHF RFID is used when precise identification is needed at a distance.
While computer vision is increasingly used for this purpose, UHF RFID is still 
an attractive option going forward in markets where:

- Concerns about privacy discourage use of video monitoring (e.g. inside the home).
- There exists a lack of repeatable visual identifiers (e.g. skiiers with masked faces).
- Identification must be kept in a secure and hidden location (e.g. inside of tires).

It is our hope that researchers and hobbyists alike can use the S.U.R.F.E.R. platform
to explore novel use cases of UHF RFID.

# Are there other types of RFID?

<center><img src="https://github.com/surfer-rfid/surfer-rfid.github.io/blob/main/LF_RFID_Tag_011921.png" width="50%"></center>

Yes, High-Frequency (HF) tags are often used for hotel key card and book tracking.
Low-frequency (LF) tags are often used for animal tracking and key fobs.
The ranges and data rates of these systems are substantially smaller than for UHF RFID; 
however, the lower frequency confers other advantages such as good performance near objects
made of metal or living tissue.

# What is Software-Defined?

<center><img src="https://github.com/surfer-rfid/surfer-rfid.github.io/blob/main/SDR_Concept_Cartoon_011821.png" width="50%"></center>

Software-defined refers to a method of building electronic systems with 
non-application-specific physical components and adding specificity through 
programmable means. A software-defined radio system typically contains a 
wideband radio transceiver circuit which exposes raw data bits at its
digital interface, a field-programmable gate array (FPGA), and some sort of
higher-level computing element such as a microcontroller unit (MCU).

For example, while S.U.R.F.E.R. has special circuitry to help it operate 
as a UHF RFID reader, it could just as easily operate as a utility montoring 
hub or a radio control in the 860-960MHz range with new MCU and FPGA flash images.

Software-defined systems are advantageous over systems comprised of hardened
ASICs in terms of flexibility, and often in terms of economic considerations.

# Flexibility

<center><img src="https://github.com/surfer-rfid/surfer-rfid.github.io/blob/main/SDR_Change_Cartoon_011821.png" width="50%"></center>

Software-defined systems provide flexibility in two ways:

1. Flexibility through choice of programming.
2. Flexibility through choice of component selection.

The first of these has already been discussed. 
Within a given application, however, programming permits:

- Over-the-air feature and bug updates to hardware.
- Easy, real-time, experimentation with novel system modifications.

Flexibility through choice of component selection can mean:

- Reduced risk of part obsolecence or lack of availability.
Sometimes chip product lines are discontinued or are purchased by a vendor
who makes working with the chip difficult. On the other hand, it's safe
to assume that there will always be publicly available flexible radio chips, FPGAs,
and MCUs with extensive documentation.

- Balh Blah
More blah


# Economical






