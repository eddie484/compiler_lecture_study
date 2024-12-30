# compiler_lecture_study
컴파일러 개론 강의에서 배운 내용을 정리합니다.

## Index

1. Lexical Analysis
- 어휘분석이란
- 정규표현식
- Token을 식별하는 프로그램 설계
- 어휘분석기 만들기

2. Parsing
- 구문을 나타내기
- 구문에서 문장을 만들기
- 모호성
- 유도를 이용한 구문분석

3. Topdown Parsing
- LL 파싱
- FIRST
- FOLLOW
- LL 문법
- 구문분석기 만들기
- 기계식 구문분석기 만들기

4. Bottomup Parsing
- Shift Reduce
- Shift-Reduce Parsing
- 구문분석 도구 Yacc
- LR(0) 파싱테이블
- 파싱테이블의 의미와 SLR 파서
- LR(1) 파서
- LALR 파서와 구문분석기 정리
  
5. Tools After Syntax Analysis - SDD & AST
- SDD
- AST
  
6. IR Basic
- IR 이란?
- IR 예
- IR 예 - Stack Machine code, Tree Code

7. IR Translation
- To 3-addr code (expr)
- To 3-addr code (statement)
- To 3-addr code (statement expression, nested expression)
- Storage Management
- Stack Management
- Stack Management 코드 생성

8. Semantic Analysis
- Semantic Analysis - Symbol Tables
- Semantic Analysis - Symbol Tables Implementation
- Semantic Analysis - Type Checking
- Semantic Analysis - Type 유도트리

9. Machine dependent processing
- Instruction Selection
- Register Allocation
- Instruction Scheduling

10. Analysis and optimization
- Control Flow Analysis
- Optimization
- Dataflow Analysis

11. Extra
- AOT, JIT 컴파일러
