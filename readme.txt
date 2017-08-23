This site generates an svg file in the shape of the snowboard specs provided via ajax api.



These are the data elements that will be sent via api

	graphic_id 			INT(11)
	boardSpecId INT
	designId INT(11)
	totalLength INT(4)
	noseLength INT(4)
	tailLength INT(4)
	stanceWidth INT(4)
	sidecutRadius INT(5)
	heelsideSidecutRadiusDifference INT(5)
	waistWidth INT(4)
	taper INT(3)
	stanceSetback INT(4)
	noseShape VARCHAR(32)
	tailShape VARCHAR(32)
	sideShape VARCHAR(32)
	svgId				INT
	designId			INT (11)
	designHash		VARCHAR (16)
	svgShape			VARCHAR (1000)
