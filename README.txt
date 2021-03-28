README.txt

expectation maximization (EM) maximum likelihood (ML) general linear model (GLM)

includes noise and clipping censoring of data, station corrections, and correlation model for path effects between events as a function of event separation

Three examples Example0 (single event magnitude) Example1 (network magnitudes) and Example2 (log-moments) illustrate usage

See UNIX style man page mlglm.man 

Uses EM algorithm with bootrapping to solve GLM

Compiles with gfortran on MacOS Catalina
	- no idea what is required to compile on other platforms
	- see file compile

Example0
Example1
Example2
README.txt
SRR.h
SVD.f
bjdaz.f
bootem10.f
compile
dmatrix.f
embob10.f
glat.f
mcorr6.f
mlglm.1
mlglm.man
mlglm10
mlglm10.f
p.f
prmt.h
probf.f
prsvd.f
ranpar.f
rdreg.f
rdstcor.f
region.f
svdcomp.f
