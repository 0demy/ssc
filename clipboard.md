
for mcq: 
: show answer: hide answer

cq Templates
Type One: CQ (4 questions: 1+2+3+4)
scene:
q1:
q2:
q3:
q4:

Type One: CQ3 (3 questions: 2+4+4)
scene:
q1:
q2:
q3:
q4:


mcq template



        {{ $currentSection := .Section }} 
        {{ $currentSection }}


        {{/*  {{ $currentSection := .Section }} 
        {{ $localMenu := "" }} */}}

        {{ if eq .Section "discrete-mathematics"}}
            {{ $localMenu := "discrete-mathematics" }}
            {{ $localMenu }}
        {{ else }}
            {{ $localMenu := "local" }}
            {{ $localMenu }}
        {{ end}}

          {{/*{{ if eq $currentSection "discrete-mathematics" }}
            {{ $localMenu := "discreteMathematics" }}
        {{ else }}
            {{ $localMenu := "local" }}
        {{ end }}  */}}
        