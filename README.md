
This is a guide to encoding and decoding Trusted Codon Fingerprint (TCF)using the demo program for windows.
 
File preparation:
1. If you want to encode TCF, please refer to the encode.json file format in the data folder, where "gene" is the gene sequence to be encoded, "gene_id" is the ID of the host cells, and "payload" is the genomic sequence which has a hash linkage with the encoded gene. 
2. If you want to decode TCF, please refer to decode.json file format in data folder, where "reads_seq" is the sequence to be decoded, and "reads_id" is the serial number for each sequence.

program execution:
1. Command: ............\Trusted_Codon_Fingerprint\Release_x64> .\GTPM_FA.exe ..\datas\GTPM-params.json
2. Params in GTPM-params.json: "function"(Execution status: 0=off, 1=on). For example, to perform encoding, adjust the number after "ENCODE" to "1".
3. Encoding result: After executing "ENCODE", the latest gene_info.txt, and encode_result.json files will be generated in the datas folder.
4. Decoding result: After executing "DECODE", the latest gene_info.txt and decode_result.csv files will be generated in the datas folder.

This software is licensed exclusively for academic research.
The use of this software for commercial purposes or non-profit applications is expressly prohibited.

