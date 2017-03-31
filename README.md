# Read file from csv format
file = read.csv("C:\\Users\\Megatron\\Desktop\\file.csv",header=T,sep=",")
head(file)

attach(global)
file_columns =  cbind(global[1],global[3],global[4],global[5],global[6],global[58])
head(file_columns)


