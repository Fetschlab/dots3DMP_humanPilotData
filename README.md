# dots3DMP_humanPilotData
data presented in forthcoming issue of Phil Trans B; will update description & add link here

filename: Jerjian_Fetsch_humanData_forPTB.mat

Pilot human data from visual-vestibular heading discrim task with RT and confidence judgments
Submitted to Phil Trans B theme issue on multisensory decision making

Steven Jerjian, Devin Harsch, Chris Fetsch - 03-25-23


fields in struct 'data':

choice : 1=left, 2=right
heading : in degrees, negative = leftward, positive = rightward
coherence : visual motion coherence
modality : stimulus modality, ves=1, vis=2, comb=3
delta : conflict angle (deg), positive = vis to the right
RT : reaction time (s)
correct : 0=incorr, 1=corr
conf : continuous scale confidence rating (saccadic end point as a fraction of vertical gradient bar)
