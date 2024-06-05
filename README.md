# Datasets Used for Analyzing and Manipulating Metadata in L01 & AFF4-L

This repository contains datasets and supplementary materials used for verifying and manipulating metadata in logical image formats. The primary focus is on identifying and manipulating the metadata of L01 and AFF4-L formats to evaluate their integrity and originality.

The datasets in this repository were used to conduct tests for the paper titled "Revisiting Logical Image Formats for Future Digital Forensics: A Comprehensive Analysis on L01 and AFF4-L." This paper has been submitted to DFRWS APAC 2024 and is planned to be made publicly available in the near future.

### Appendix

#### L01 file format
![L01_file_format](https://github.com/ggeng2/Logical_Image_Dataset/assets/98377556/2c1d5b7b-3dd7-47c6-8bd4-bfc5f0a9f23f)

#### Metadata manipulation test results

##### AFF4-L
<table style="border-collapse: collapse; border: none; border-spacing: 0px;">
	<tr>
		<td rowspan="2" colspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Target
		</td>
		<td colspan="2" style="border-bottom: 0px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Image File Metadata
		</td>
		<td colspan="2" style="border-bottom: 0px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Original File Metadata
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Image Stream ARN
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			File Image ARN
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Original File Name
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Original File Hash (SHA1)
		</td>
	</tr>
	<tr>
		<td rowspan="3" style="border-bottom: 1px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Simple
			<br>
			Manipulation
		</td>
		<td style="border-bottom-color: rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			Before
		</td>
		<td style="border-bottom-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			dc863c98-10b6-4aec
			<br>
			-baf5-e7ed80b6cf2b
		</td>
		<td style="border-bottom-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			5e7a4e9e-6183-4ad5
			<br>
			-b9bc-ce45c68d6d22
		</td>
		<td style="border-bottom-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			origin.txt
		</td>
		<td style="border-bottom-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			1a96f202899f9c37a8b0
			<br>
			ac324525b9e8f67e0513
		</td>
	</tr>
	<tr>
		<td style="padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			After
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			fbd50a9e-3baa-400a
			<br>
			-a370-8eaddd1ae14d
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			9eee991e-7845-4a60
			<br>
			-b452-8b448b56a4b8
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			target.txt
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			0xFF
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 1px solid black; border-top-color: rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			Result
		</td>
		<td style="border-bottom: 1px solid black; border-top-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			△
		</td>
		<td style="border-bottom: 1px solid black; border-top-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			△
		</td>
		<td style="border-bottom: 1px solid black; border-top-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			△
		</td>
		<td style="border-bottom: 1px solid black; border-top-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			△
		</td>
	</tr>
	<tr>
		<td rowspan="3" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #f0f0f0;">
			Elaborate
			<br>
			Manipulation
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			Before
			<br>
			CRC
		</td>
		<td colspan="4" style="text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			container.description : 0xC065AB16
			<br>
			information.turtle : 0x23FDE4FA
		</td>
	</tr>
	<tr>
		<td style="border-top-color: rgb(0, 0, 0); border-bottom-color: rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			After
			<br>
			CRC
		</td>
		<td colspan="4" style="border-top-color: rgb(0, 0, 0); border-bottom-color: rgb(0, 0, 0); text-align: center; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			container.description : 0x51642E60
			<br>
			information.turtle : 0xD3CA6135
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			Result
		</td>
		<td style="text-align: center; border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			O
		</td>
		<td style="text-align: center; border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			O
		</td>
		<td style="text-align: center; border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			O
		</td>
		<td style="text-align: center; border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt; background-color: #ffffff;">
			O
		</td>
	</tr>
</table>

##### L01
<table style="border-collapse: collapse; border: none; border-spacing: 0px;">
	<tr>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Section
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Category
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Identifier
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			EnCase
			<br>
			Item
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Remark
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Action
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Before
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			After
		</td>
		<td colspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Result
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Simple
			<br>
			Manipulation
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			Elaborate
			<br>
			Manipulation
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			volume
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			GUID
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			12F9E229242C27AA
			<br>
			899E5C5D973E25F2
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			12F9E229242C27AA
			<br>
			899E5C5D973E25F2
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
	</tr>
	<tr>
		<td rowspan="16" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			ltree
		</td>
		<td rowspan="5" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			sources
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			n
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Name
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			C
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			W
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			C
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			ah
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			MD5
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			always 0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			sh
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			SHA1
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			always 0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			12345678901234567890
			<br>
			12345678901234567890
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			aq
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Acquisition
			<br>
			date and time
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			always an
			<br>
			empty value&nbsp;
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			add
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			2023-10-24 20:37:12
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td rowspan="11" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			file
			<br>
			entries
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			mid
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			GUID
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			94BC96591168158B
			<br>
			A31CDBD37FE10763
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			94BC96591168158B
			<br>
			A31CDBD37FE10763
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			cr
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			File
			<br>
			Created
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			2023-06-29 18:12:12
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			2023-10-23 22:17:12
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			2023-06-29 18:12:12
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			dl
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Deletion
			<br>
			date and time
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			always an
			<br>
			empty value
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			add
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			2023-10-24 20:37:12
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			ha
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			MD5
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			MD5 option
			<br>
			unchecked
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			ha
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			MD5
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			MD5 option
			<br>
			checked
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			7a2188299adf0ae1
			<br>
			290121cefb054709
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			7a2188299adf0ae1
			<br>
			290121cefb054709
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			sha
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			SHA1
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			always 0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			0
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			12345678901234567890
			<br>
			12345678901234567890
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			n
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			Name
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			ltree.xlsx
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			abcde.fghi
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			ltree.xlsx
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			△
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			O
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			data
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			GUID
		</td>
		<td rowspan="2" style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			12F9E229242C27AA
			<br>
			899E5C5D973E25F2
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			12F9E229242C27AA
			<br>
			899E5C5D973E25F2
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 0px solid rgb(0, 0, 0); padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			map
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			GUID
		</td>
		<td rowspan="2" style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			alter
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			94BC96591168158B
			<br>
			A31CDBD37FE10763
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			1234567890123456
			<br>
			7890123456789012
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			delete
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			94BC96591168158B
			<br>
			A31CDBD37FE10763
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			-
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
		<td style="border-bottom: 2px solid black; padding-right: 3pt; padding-left: 3pt;">
			X
		</td>
	</tr>
</table>



