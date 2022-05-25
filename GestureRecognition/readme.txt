This is a hand gesture recognition module 

this is an added addition to what google provides you with mediapipe 

the first step is to add the node to the hand_renderer_cpu.pbtxt in the mediapipe/mediapipe/graphs/hand_tracking/subgraphs/handrenderer_cpu.pbtxt Or alternatively gpu 

node{
  calculater: "HandTrackingCalculator"
  input_stream: "LANDMARKS:multi_hand_landmarks"
  input_stream: ""
	
}

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
