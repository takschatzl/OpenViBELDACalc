%  
% :-:-:-:-:-:-:-:-:-: Up to date INFO :-:-:-:-:-:-:-:-:  
%  
% (25/Feb/2016) Caution! Function LDAfuncex_P300 and LDAfuncex_SSVEP has not been  
% public so far because of the author rights. Those of codes are modified  
% version (implemented shrinkage algorhythm or so) of the LDA algorithm  
% function which released in MATLAB central. Please, refer to the following link.  
%  
% http://www.mathworks.com/matlabcentral/fileexchange/29673-lda--linear-discriminant-analysis  
%  
% :-:-:-:-:-:-:-:-:-: Instruction :-:-:-:-:-:-:-:-:-:  
%  
% main_LDAcalc(ARG_1(char), ARG_2(char), ARG_3(double), ARG_4(double))  
%  
% === Input ===  
%  
% ARG_1 directory_Training(char): File directory location which has training csv files generated by OpenViBE  
% ARG_2 directory_Trial(char): File directory location which has trial csv files generated by OpenViBE  
% ARG_3 savePNG(double): If you want to save the result of the graph, this value should be set to 1, othewise 0  
% ARG_4 identifier(double): Value of file identifier, if(SSVEP) value = 1; elseif(P300) value = 2;  
%  
% === Output ===  
%  
% Figure: Probability of each duration versus each targets (Grid)  
%  
% === Example ===  
%  
% MATLAB > main_LDAcalc('../User/DirectoryName/Target', '../User/DirectoryName/Trial', 1, 1)  
% MATLAB > main_LDAcalc('../User/DirectoryName/Target', '../User/DirectoryName/Trial', 0, 0)  
%  
% :-:-:-:-: (C) Takumi Kodama, University of Tsukuba, Japan :-:-:-:-:  
