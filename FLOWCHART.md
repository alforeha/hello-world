flowchart TD

%% --- LIFE ESSENTIALS ---
subgraph LIFE ESSENTIALS
P1[Physical]
P2[Mental]
P3[Financial]
P4[Social]
P5[Environmental]
P6[Logistical]
P7[Legal]
end

%% --- ENGINES ---
subgraph ENGINES
E1[App]
E2[Income Positioning]
E3[Housing]
E4[Licensure]
end

%% --- RELATIONSHIPS ---
P1 --> E1
P2 --> E1
P3 --> E2
P3 --> E3
P5 --> E3
P6 --> E3
P7 --> E4
P2 --> E4
P3 --> E4
