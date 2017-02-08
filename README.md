# ItrisCreditoPersonal
Query para armar la migración de créditos personal.

By Goro&Pasculeta
Haciendo historia
;-)

# Estas es la estructura que tiene que tener la tabla que almacena los datos de crédito personal del cliente

Column_name	Type	Computed	Length	Prec	Scale	Nullable	TrimTrailingBlanks	FixedLenNullInSource	Collation
ID	int	no	4	10   	0    	no	(n/a)	(n/a)	NULL
ID_CLIENTE	varchar	no	30	     	     	yes	yes	yes	Modern_Spanish_CI_AS
TIP_COM_AP	varchar	no	30	     	     	yes	yes	yes	Modern_Spanish_CI_AS
NUM_COM_AP	varchar	no	30	     	     	yes	yes	yes	Modern_Spanish_CI_AS
FECHA_FACT	datetime	no	8	     	     	yes	(n/a)	(n/a)	NULL
FECHA_VENC	datetime	no	8	     	     	yes	(n/a)	(n/a)	NULL
SALDO	decimal	no	9	12   	0    	yes	(n/a)	(n/a)	NULL
CUOTAS	int	no	4	10   	0    	yes	(n/a)	(n/a)	NULL
SUCURSAL	varchar	no	50	     	     	yes	yes	yes	Modern_Spanish_CI_AS
C_EMISOR	varchar	no	3	     	     	yes	yes	yes	Modern_Spanish_CI_AS
